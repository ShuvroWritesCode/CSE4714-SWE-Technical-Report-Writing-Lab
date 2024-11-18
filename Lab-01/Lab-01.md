Here is a curated note for your LaTeX class in Markdown format for easy revision:

```markdown
# LaTeX Notes for Technical Report Writing

## Document Structure
```latex
\documentclass{article}
\usepackage{times} % Use Times New Roman font
\usepackage[margin=1in]{geometry} % Set 1-inch margins
\title{An Intro To \LaTeX}
\author{Your Name}
\date{\today}

\begin{document}
    \maketitle % Generates the title
\end{document}
```

---

## Title Page
```latex
\begin{titlepage}
    \maketitle % Creates a standalone title page
\end{titlepage}
```

---

## Abstract
```latex
\begin{abstract}
    This is an abstract text. Use this section to summarize the document.
\end{abstract}
```

---

## Sections and Subsections
```latex
\section{Introduction}
This is the introduction section.

\subsection{Introduction Subsection 1}
Details for the first subsection.

\subsubsection{Introduction Subsubsection 1}
Details for the first subsubsection.

\section{Second Section}
This is the second section.

\subsection{Subsection 2}
Details for the second subsection.
```

---

## Text Formatting
```latex
This is \emph{italic text}. \\
This is \textbf{bold text}. \\
This is \textit{\textbf{italic and bold text}}. \\
This is \underline{underlined text}.
```

---

## Alignment Options
- **Flushright:**
    ```latex
    \begin{flushright}
        Aligned to the right.
    \end{flushright}
    ```

- **Other options:** `\raggedleft`, `\raggedright`, `\center`.

---

## Lists
### Unordered List
```latex
\begin{itemize}
    \item First Item
    \item Second Item
        \begin{itemize}
            \item Nested Item 1
            \item Nested Item 2
        \end{itemize}
    \item Third Item
\end{itemize}
```

### Ordered List
```latex
\begin{enumerate}
    \item First Item
    \item Second Item
        \begin{enumerate}
            \item Nested Item 1
            \item Nested Item 2
        \end{enumerate}
    \item Third Item
\end{enumerate}
```

---

## Font Sizes
```latex
\begin{tiny}
    This is a tiny text.
\end{tiny}

\begin{small}
    This is a small text.
\end{small}

This is a normal text.

\begin{large}
    This is a large text.
\end{large}

\begin{Large}
    This is a Large text.
\end{Large}

\begin{Huge}
    This is a Huge text.
\end{Huge}
```

---

## Placeholder Text (Using kantlipsum)
```latex
\usepackage{kantlipsum} % For dummy text
\kant[1-2] % Generates placeholder text from paragraphs 1 to 2.
```

---

## Geometry (Margins)
### Equal Margins
```latex
\usepackage[margin=1in]{geometry}
```

### Custom Margins
```latex
\usepackage[top=1in, bottom=1in, left=0.5cm, right=0.5cm]{geometry}
```

---

## Key Concepts
- **Environment**: Structures like `\begin{itemize}` and `\end{itemize}` define a specific type of formatting, similar to HTML tags.
- **Commands**: Predefined commands like `\maketitle`, `\section`, and `\textbf` add specific functionalities or styles to your document.

This Markdown note provides concise explanations and examples for each topic covered in your class, making it perfect for quick revision.
```
