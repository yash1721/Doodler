\documentclass{article}
\usepackage{hyperref}

\begin{document}

\title{Doodler - Multiplayer Web Game}

\maketitle

<!-- \section*{Team Members}
\begin{itemize}
    \item Ankita Verma - \href{https://github.com/ankita-46}{https://github.com/ankita-46}
    \item Priyanshu Singh - \href{https://github.com/pssingh1434131}{https://github.com/pssingh1434131}
    \item Madhubrat Dixit - \href{https://github.com/Madhubrat1562}{https://github.com/Madhubrat1562}
\end{itemize} -->

\section*{Project Overview}
\textbf{Doodler} is an engaging multiplayer web game where one participant illustrates an object, and fellow players attempt to guess the object's name based on the drawing. Players earn points based on the accuracy of their guesses, fostering an interactive and fun-filled gaming experience.

\section*{Video Demonstration}
\href{https://drive.google.com/drive/folders/1ijB97ziIfwLNaNVH4vWFgyzaD0HsueDK}{Watch the video demonstration here.}

\section*{Screenshots}
\href{https://drive.google.com/drive/folders/122Nu5mHcoJPQwgyVg9vAnTSFg_o1yeo7}{View images from the site here.}

\section*{Current Features}
\begin{itemize}
    \item User authentication and authorization.
    \item Profile page where users can view and edit their profile, change avatar, name, and password.
    \item Friend feature allowing users to send and receive friend requests in real time.
    \item External chat feature outside the in-game chat.
    \item Two game modes:
    \begin{itemize}
        \item \textbf{Play with Friends:} Generate or join a room, invite friends with a code.
        \item \textbf{Play Online:} Join and play with random people; two players selected in real-time.
    \end{itemize}
    \item Multiplayer game with up to 5 players; one player draws while others guess and earn points based on accuracy.
    \item In-game chat with profanity filter; host can restrict chat and block users sending profane messages.
    \item Host can kick out other users.
    \item Users can download and share the whiteboard image.
    \item Whiteboard tools: pencil, eraser, line, shapes (square, rectangle, circle, ellipse, trapezium), color picker, thickness adjuster.
    \item Undo and Redo drawing feature.
    \item Three rounds per game; each player presents for one minute.
    \item Game history is saved in the database; users can view history on the homepage.
\end{itemize}

\section*{Upcoming Features}
\begin{itemize}
    \item Collaborative drawing.
    \item Mobile compatibility.
    \item Play with a computer using an ML model.
    \item Advanced shapes and painting tools on the whiteboard.
\end{itemize}

\section*{Tech Stack}
\begin{itemize}
    \item \textbf{CLIENT:} React.js
    \item \textbf{BACKEND:} Node.js, Express.js
    \item \textbf{DATABASE:} MongoDB
    \item \textbf{LIBRARIES:} Socket.io, Rough.js
\end{itemize}

\section*{How to Run on the Local System}
\begin{enumerate}
    \item Clone the main branch to your local system.
    \item Run \texttt{npm i} in the following directories:
    \begin{itemize}
        \item Doodler
        \item Doodler/client
        \item Doodler/server
    \end{itemize}
    \item Create and initialize your \texttt{.env} file in \texttt{Doodler/server}.
    \item In the \texttt{Doodler} directory, run \texttt{npm start} to run both the server and client simultaneously.
\end{enumerate}

\end{document}
