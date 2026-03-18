\documentclass{article}

% Language setting
% Replace `english' with e.g. `spanish' to change the document language
\usepackage[spanish]{babel}

% Set page size and margins
% Replace `letterpaper' with `a4paper' for UK/EU standard size
\usepackage[letterpaper,top=2cm,bottom=2cm,left=3cm,right=3cm,marginparwidth=1.75cm]{geometry}

% Useful packages
\usepackage{amsmath}
\usepackage{graphicx}
\usepackage[colorlinks=true, allcolors=blue]{hyperref}

\title{PROYECTO FINAL DE ESTUDIO}
\author{AGUIRRE SIMIONATO Juan Marcos}

\begin{document}
\maketitle

\begin{abstract}
Your abstract.
\end{abstract}

\section{Introduction}

Your introduction goes here! Simply start writing your document and use the Recompile button to view the updated PDF preview. Examples of commonly used commands and features are listed below, to help you get started.

Once you're familiar with the editor, you can find various project settings in the Overleaf menu, accessed via the button in the very top left of the editor. To view tutorials, user guides, and further documentation, please visit our \href{https://www.overleaf.com/learn}{help library}, or head to our plans page to \href{https://www.overleaf.com/user/subscription/plans}{choose your plan}.

\section{Some examples to get started}

\subsection{How to create Sections and Subsections}

Simply use the section and subsection commands, as in this example document! With Overleaf, all the formatting and numbering is handled automatically according to the template you've chosen. If you're using the Visual Editor, you can also create new section and subsections via the buttons in the editor toolbar.

\subsection{How to include Figures}

First you have to upload the image file from your computer using the upload link in the file-tree menu. Then use the includegraphics command to include it in your document. Use the figure environment and the caption command to add a number and a caption to your figure. See the code for Figure \ref{fig:frog} in this section for an example.

Note that your figure will automatically be placed in the most appropriate place for it, given the surrounding text and taking into account other figures or tables that may be close by. You can find out more about adding images to your documents in this help article on \href{https://www.overleaf.com/learn/how-to/Including_images_on_Overleaf}{including images on Overleaf}.

\begin{figure}
\centering
\includegraphics[width=0.25\linewidth]{frog.jpg}
\caption{\label{fig:frog}This frog was uploaded via the file-tree menu.}
\end{figure}

\subsection{How to add Tables}

Use the table and tabular environments for basic tables --- see Table~\ref{tab:widgets}, for example. For more information, please see this help article on \href{https://www.overleaf.com/learn/latex/tables}{tables}.

\begin{table}
\centering
\begin{tabular}{l|r}
Item & Quantity \\\hline
Widgets & 42 \\
Gadgets & 13
\end{tabular}
\caption{\label{tab:widgets}An example table.}
\end{table}

\subsection{How to add Comments and Track Changes}

Comments can be added to your project by highlighting some text and clicking ``Add comment'' in the top right of the editor pane. To view existing comments, click on the Review menu in the toolbar above. To reply to a comment, click on the Reply button in the lower right corner of the comment. You can close the Review pane by clicking its name on the toolbar when you're done reviewing for the time being.

Track changes are available on all our \href{https://www.overleaf.com/user/subscription/plans}{premium plans}, and can be toggled on or off using the option at the top of the Review pane. Track changes allow you to keep track of every change made to the document, along with the person making the change.

\subsection{How to add Lists}

You can make lists with automatic numbering \dots

\begin{enumerate}
\item Like this,
\item and like this.
\end{enumerate}
\dots or bullet points \dots
\begin{itemize}
\item Like this,
\item and like this.
\end{itemize}

\subsection{How to write Mathematics}

\LaTeX{} is great at typesetting mathematics. Let $X_1, X_2, \ldots, X_n$ be a sequence of independent and identically distributed random variables with $\text{E}[X_i] = \mu$ and $\text{Var}[X_i] = \sigma^2 < \infty$, and let
\[S_n = \frac{X_1 + X_2 + \cdots + X_n}{n}
      = \frac{1}{n}\sum_{i}^{n} X_i\]
denote their mean. Then as $n$ approaches infinity, the random variables $\sqrt{n}(S_n - \mu)$ converge in distribution to a normal $\mathcal{N}(0, \sigma^2)$.


\subsection{How to change the margins and paper size}

Usually the template you're using will have the page margins and paper size set correctly for that use-case. For example, if you're using a journal article template provided by the journal publisher, that template will be formatted according to their requirements. In these cases, it's best not to alter the margins directly.

If however you're using a more general template, such as this one, and would like to alter the margins, a common way to do so is via the geometry package. You can find the geometry package loaded in the preamble at the top of this example file, and if you'd like to learn more about how to adjust the settings, please visit this help article on \href{https://www.overleaf.com/learn/latex/page_size_and_margins}{page size and margins}.

\subsection{How to change the document language and spell check settings}

Overleaf supports many different languages, including multiple different languages within one document.

To configure the document language, simply edit the option provided to the babel package in the preamble at the top of this example project. To learn more about the different options, please visit this help article on \href{https://www.overleaf.com/learn/latex/International_language_support}{international language support}.

To change the spell check language, simply open the Overleaf menu at the top left of the editor window, scroll down to the spell check setting, and adjust accordingly.

\subsection{How to add Citations and a References List}

You can simply upload a \verb|.bib| file containing your BibTeX entries, created with a tool such as JabRef. You can then cite entries from it, like this: \cite{greenwade93}. Just remember to specify a bibliography style, as well as the filename of the \verb|.bib|. You can find a \href{https://www.overleaf.com/help/97-how-to-include-a-bibliography-using-bibtex}{video tutorial here} to learn more about BibTeX.

If you have an \href{https://www.overleaf.com/user/subscription/plans}{upgraded account}, you can also import your Mendeley or Zotero library directly as a \verb|.bib| file, via the upload menu in the file-tree.

\subsection{Good luck!}

We hope you find Overleaf useful, and do take a look at our \href{https://www.overleaf.com/learn}{help library} for more tutorials and user guides! Please also let us know if you have any feedback using the \textbf{Contact us} link at the bottom of the Overleaf menu --- or use the contact form at \url{https://www.overleaf.com/contact}.

\bibliographystyle{alpha}
\bibliography{sample}

\end{document}




CV



% a mashup of hipstercv, friggeri and twenty cv
% https://www.latextemplates.com/template/twenty-seconds-resumecv
% https://www.latextemplates.com/template/friggeri-resume-cv

\documentclass[lighthipster]{simplehipstercv}
% available options are: darkhipster, lighthipster, pastel, allblack, grey, verylight, withoutsidebar
% withoutsidebar
\usepackage[utf8]{inputenc}
\usepackage[default]{raleway}
\usepackage[margin=1cm, a4paper]{geometry}


%------------------------------------------------------------------ Variablen

\newlength{\rightcolwidth}
\newlength{\leftcolwidth}
\setlength{\leftcolwidth}{0.23\textwidth}
\setlength{\rightcolwidth}{0.75\textwidth}

%------------------------------------------------------------------
\title{New Simple CV}
\author{\LaTeX{} Ninja}
\date{June 2019}

\pagestyle{empty}
\begin{document}


\thispagestyle{empty}
%-------------------------------------------------------------

\section*{Start}

\simpleheader{headercolour}{Juan Marcos}{Aguirre Simionato}{Estudiante Ingeniería}{white}



%------------------------------------------------

% this has to be here so the paracols starts..
\subsection*{}
\vspace{4em}

\setlength{\columnsep}{1.5cm}
\columnratio{0.23}[0.75]
\begin{paracol}{2}
\hbadness5000
%\backgroundcolor{c[1]}[rgb]{1,1,0.8} % cream yellow for column-1 %\backgroundcolor{g}[rgb]{0.8,1,1} % \backgroundcolor{l}[rgb]{0,0,0.7} % dark blue for left margin

\paracolbackgroundoptions

% 0.9,0.9,0.9 -- 0.8,0.8,0.8


\footnotesize
{\setasidefontcolour
\flushright
\begin{center}
    \roundpic{jack.png}
\end{center}

\bg{cvgreen}{white}{Sobre mi}\\[0.5em]

{\footnotesize
 Estudiante de Ingeniería Industrial con interés en optimización de procesos, análisis de datos y mejora continua. Me enfoco en entender cómo funcionan los sistemas productivos para identificar ineficiencias y proponer soluciones prácticas. Manejo herramientas analíticas y tengo una mentalidad orientada a resultados. Busco desarrollarme en entornos donde pueda aplicar conocimientos técnicos y generar impacto real.}
\bigskip

\bg{cvgreen}{white}{personal} \\[0.5em]
Juan Marcos Aguirre

Nacionalidad: Argentino 

2002

\bigskip




\bigskip

\bg{cvgreen}{white}{Interests}\\[0.5em]

\lorem
\bigskip

\bg{cvgreen}{white}{Interests}\\[0.5em]

\texttt{Gestión} ~/~ \texttt{Proyectos} ~/~ \texttt{Rendimiento}


\vspace{4em}

\infobubble{\faAt}{cvgreen}{white}{juanmaaguirre125}
\infobubble{\faTwitter}{cvgreen}{white}{@juanmaaguirre12}
\infobubble{\faFacebook}{cvgreen}{white}{Juan Marcos Aguirre}
\infobubble{\faGithub}{cvgreen}{white}{AguirreJuanMarcos}

\phantom{turn the page}

\phantom{turn the page}
}
%-----------------------------------------------------------
\switchcolumn

\small
\section*{Resumen}

\begin{tabular}{r| p{0.5\textwidth} c}
    \cvevent{2020--2026}{Estudiante de Ingienería}{Estudiante}{UNCuyo \color{cvred}}{Estudiante de Ingienería Industrial.}{disney.png} \\
    \cvevent{--2019}{Bachillerato en Economíal}{Estudiante}{I.P.V.B \color{cvred}}{\lorem\lorem}{medal.jpeg}
\end{tabular}
\vspace{3em}

\begin{minipage}[t]{0.35\textwidth}
\section*{Grados}
\begin{tabular}{r p{0.6\textwidth} c}
    \cvdegree{2026}{Estudiante de Ingeniería}{Regular}{UNCuyo \color{headerblue}}{}{disney.png} \\
    \cvdegree{2020}{Bachillearto Economía}{Certificado}{Mendoza \color{headerblue}}{}{medal.jpeg} \\
    \cvdegree{--}{Cursos}{Certificados}{Mendoza \color{headerblue}}{}{medal.jpeg}
\end{tabular}
\end{minipage}\hfill



\section*{Cursos}
\begin{tabular}{r| p{0.5\textwidth} c}
    \cvevent{2024}{Curso de electricidad y técnico en Aires Acondicionados}{Certificado}{Mendoza \color{cvred}}{Finally got the goddamn ship back.}{} \\
    \cvevent{2025}{Curso Workover}{Certificado}{Tortuga \color{cvred}}{  \lorem}{medal.jpeg} \\
\end{tabular}
\vspace{3em}

\begin{minipage}[t]{0.3\textwidth}
\section*{Certificados}
\begin{tabular}{>{\footnotesize\bfseries}r >{\footnotesize}p{0.55\textwidth}}
    2026 & Certificados de Cursos mencionados anteriormente \\

\end{tabular}
\bigskip

\section*{Idiomas}
\begin{tabular}{l | ll}
\textbf{Español} & C2 & {\phantom{x}\footnotesize idioma nativo} \\

\textbf{Inglés} & C2 & \pictofraction{\faCircle}{cvgreen}{1}{black!30}{3}{\tiny} \\

\end{tabular}
\bigskip

\end{minipage}\hfill
\begin{minipage}[t]{0.3\textwidth}


\bigskip



\end{minipage}






\vfill{} % Whitespace before final footer

%----------------------------------------------------------------------------------------
%	FINAL FOOTER
%----------------------------------------------------------------------------------------
\setlength{\parindent}{0pt}
\begin{minipage}[t]{\rightcolwidth}
\begin{center}\fontfamily{\sfdefault}\selectfont \color{black!70}
{\small Juan Aguirre \icon{\faEnvelopeO}{cvgreen}{} juanmaaguirre125 \icon{\faMapMarker}{cvgreen}{} Mendoza Argentina \icon{\faPhone}{cvgreen}{} 2616932970 \newline\icon{\faAt}{cvgreen}{} \protect\url{juanmaaguirre125@gmail.com}
}
\end{center}
\end{minipage}

\end{paracol}

\end{document}

