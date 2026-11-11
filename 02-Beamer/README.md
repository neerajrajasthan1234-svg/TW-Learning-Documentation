
# Beamer Documentation

## 1. Introduction to Beamer

Beamer is a LaTeX document class used to create professional presentations and slides. It is widely used for academic presentations, seminars, lectures, and technical talks.

## 2. Features of Beamer

- Creates professional presentations.
- Supports themes and color customization.
- Allows mathematical equations.
- Supports images, tables, and lists.
- Provides automatic slide numbering.
- Supports overlays and animations.

## 3. Basic Beamer Document Structure

```latex
\documentclass{beamer}

\title{My First Presentation}
\author{Neeraj Kumar}
\institute{MNIT Jaipur}
\date{\today}

\begin{document}

\begin{frame}
    \titlepage
\end{frame}

\begin{frame}{Introduction}
    Welcome to my first Beamer presentation.
\end{frame}

\end{document}
```

## 4. Important Beamer Commands

| Command | Purpose |
|---|---|
| `\documentclass{beamer}` | Defines Beamer presentation |
| `\title{}` | Sets presentation title |
| `\author{}` | Sets author name |
| `\institute{}` | Sets institution |
| `\date{}` | Sets presentation date |
| `\begin{frame}` | Starts a slide |
| `\end{frame}` | Ends a slide |
| `\titlepage` | Displays title slide |
| `\frametitle{}` | Sets slide title |

## 5. Creating Lists in Beamer

### Unordered List

```latex
\begin{frame}{My Hobbies}
\begin{itemize}
    \item Coding
    \item Reading
    \item Photography
\end{itemize}
\end{frame}
```

### Ordered List

```latex
\begin{frame}{Steps}
\begin{enumerate}
    \item Introduction
    \item Main Content
    \item Conclusion
\end{enumerate}
\end{frame}
```

## 6. Applying Themes

Beamer provides different themes to customize presentations.

Example:

```latex
\usetheme{Madrid}
```

Other themes include:
- Berlin
- Copenhagen
- CambridgeUS
- Warsaw
- AnnArbor

## 7. Adding Mathematical Equations

```latex
\begin{frame}{Mathematics}
\[
E = mc^2
\]
\end{frame}
```

## 8. Adding Images

```latex
\begin{frame}{My Image}
\includegraphics[width=0.5\textwidth]{image.png}
\end{frame}
```

## 9. Applications of Beamer

- College presentations.
- Academic seminars.
- Research presentations.
- Classroom lectures.
- Technical conferences.

## 10. Conclusion

Beamer is a powerful LaTeX tool for creating structured, professional, and customizable presentations. It is especially useful for academic and technical presentations.
