%-------------------------
% Resume in Latex
% Author : Jake Gutierrez
% Based off of: https://github.com/sb2nov/resume
% License : MIT
%------------------------

\documentclass[letterpaper,11pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}
\usepackage{fontawesome5}
\usepackage{multicol}
\setlength{\multicolsep}{-3.0pt}
\setlength{\columnsep}{-1pt}
\input{glyphtounicode}


%----------FONT OPTIONS----------
% sans-serif
% \usepackage[sfdefault]{FiraSans}
% \usepackage[sfdefault]{roboto}
% \usepackage[sfdefault]{noto-sans}
% \usepackage[default]{sourcesanspro}

% serif
% \usepackage{CormorantGaramond}
% \usepackage{charter}


\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.6in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1.19in}
\addtolength{\topmargin}{-.7in}
\addtolength{\textheight}{1.4in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large\bfseries
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

% Ensure that generate pdf is machine readable/ATS parsable
\pdfgentounicode=1

%-------------------------
% Custom commands
\newcommand{\resumeItem}[1]{
  \item\small{
    {#1 \vspace{-2pt}}
  }
}

\newcommand{\classesList}[4]{
    \item\small{
        {#1 #2 #3 #4 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{1.0\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & \textbf{\small #2} \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubSubheading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textit{\small#1} & \textit{\small #2} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{1.001\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & \textbf{\small #2}\\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}

\renewcommand\labelitemi{$\vcenter{\hbox{\tiny$\bullet$}}$}
\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.0in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%


\begin{document}

%----------HEADING----------
% \begin{tabular*}{\textwidth}{l@{\extracolsep{\fill}}r}
%   \textbf{\href{http://sourabhbajaj.com/}{\Large Sourabh Bajaj}} & Email : \href{mailto:sourabh@sourabhbajaj.com}{sourabh@sourabhbajaj.com}\\
%   \href{http://sourabhbajaj.com/}{http://www.sourabhbajaj.com} & Mobile : +1-123-456-7890 \\
% \end{tabular*}

\begin{center}
    {\Huge \scshape Arman Shaikh} \\ \vspace{1pt}
    {\Large \textit{Java Developer}} \\ \vspace{3pt}
    \href{mailto:arman22shaikh@gmail.com}{\raisebox{-0.2\height}\faEnvelope\ \underline{arman22shaikh@gmail.com}} 
    ~$|$~ 
    \href{https://www.linkedin.com/in/arman2210/}{\raisebox{-0.2\height}\faLinkedin\ \underline{arman2210}} 
    ~$|$~ 
    \href{https://leetcode.com/codewitharman}{\raisebox{-0.2\height}\faCode\ \underline{codewitharman}} 
    ~$|$~ 
    \href{https://codewitharman.github.io/portfolio/}{\raisebox{-0.2\height}\faGlobe\ \underline{Portfolio}} 
    ~$|$~ 
    \raisebox{-0.1\height}\faPhone\ \underline{+91 7715867323}
    \vspace{-4pt}
\end{center}


%-----------PROGRAMMING SKILLS-----------
\section{Technical Skills}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{Languages}{: Java, SQL, HTML, CSS} \\
     \textbf{Frameworks}{: Spring Boot, Spring Cloud, Spring MVC, Hibernate, Spring JDBC, Bootstrap} \\
     \textbf{Databases}{: MySQL, Oracle, RDBMS} \\
     \textbf{AI / Generative AI}{: Prompt Engineering, OpenAI API Integration, AI Agents (Basics), AI-assisted Development \& Debugging (GitHub Copilot)} \\
     \textbf{Developer Tools}{: VS Code, Eclipse, STS, Postman, Maven, Beyond Compare} \\
     \textbf{Practices \& Concepts}{: RESTful APIs, Microservices, J2EE, Agile, Scrum, Git, GitHub, Bitbucket, Swagger} \\
     \textbf{Operating Systems}{: macOS, Windows, Linux} \\
    }}
 \end{itemize}
 \vspace{-16pt}

%-----------EXPERIENCE-----------
\section{Experience}
  \resumeSubHeadingListStart

    \resumeSubheading
      {Ameya Infovision}{Aug 2023 -- Present}
      {Java Developer}{Mumbai}
      \resumeItemListStart
       \resumeItem{Streamlined and enhanced RESTful web services using Spring Boot, resulting in faster response times.}
        \resumeItem{Created and implemented Java applications, transitioning from Struts to Spring Boot, which improved functionality.}
        \resumeItem{Collaborated with the cross-functional team to develop intuitive user interfaces and experiences.}
        \resumeItem{Applied Agile principles to manage tasks, meet deadlines, and drive continuous improvement through debugging.}
      \resumeItemListEnd

    \resumeSubheading
      {Prodigy DX}{Jul 2022 -- Aug 2023 }
      {Java Developer}{Thane}
      \resumeItemListStart
        \resumeItem{Contributed to application development, improving performance, scalability, and maintainability across environments.}
        \resumeItem{Provided support and troubleshooting, addressing issues promptly to ensure smooth operations and user experience.}
        \resumeItem{Resolved production issues by analyzing logs, improving system reliability and reducing downtime significantly.}
        \resumeItem{Participated in code reviews and provided feedback to improve code quality and adhere to best practices.}
    \resumeItemListEnd
    
  \resumeSubHeadingListEnd
\vspace{-16pt}

%-----------PROJECTS-----------
\section{Projects}
    \vspace{-5pt}
    \resumeSubHeadingListStart
          \resumeProjectHeading
          {\textbf{Forex Prepaid Cards Interest Calculation} $|$ \emph{Java, Spring Boot, RESTful API, Swagger}}{Jan 2025}
          \resumeItemListStart
            \resumeItem{Played a key role as a backend developer in developing and deploying a financial data processing system for Forex Cash Credit Cards, automating manual workflows and improving efficiency by approx 30\%.}
            \resumeItem{Designed and optimized RESTful APIs for real-time transaction reconciliation and automated financial posting.}
            \resumeItem{Enhanced system scalability to support multi-source data processing, ensuring high transaction throughput and improved processing timelines.}
          \resumeItemListEnd 
          \vspace{-13pt}     
        \resumeProjectHeading
              {\textbf{Axis Remit Connect} $|$ \emph{Java, Spring Boot, Spring JDBC, HTML, CSS, Bootstrap, JSP, JSTL,PL SQL}}{Feb 2024}
        \resumeItemListStart
          \resumeItem{Migrated four legacy Struts apps to Spring Boot, boosting performance, maintainability, and scalability by approx 30\%.}
          \resumeItem{Optimized financial messaging workflows to reduce delays and streamline operations.}
          \resumeItem{Revamped the UI using HTML, CSS, Bootstrap, and JSP for an intuitive, responsive reporting experience.}
        \resumeItemListEnd
         \vspace{-13pt}
        \resumeProjectHeading
          {\textbf{Claims Processing System} $|$ \emph{Java, Spring Boot, RESTful API, Redis}}{Nov 2023}
        \resumeItemListStart
          \resumeItem{Utilized Java and Spring Boot as a backend developer to design and build a centralized platform that streamlined claims processing with exceptional efficiency.}
          \resumeItem{Designed and implemented RESTful APIs to streamline claims handling and automate business workflows.}
          \resumeItem{Supported the robust monolithic architecture, streamlining deployment, maintenance, and operational efficiency.}
        \resumeItemListEnd  
          % \resumeProjectHeading
          % {\textbf{Rich Text Editor API - ICICI Bank} $|$ \emph{Java, RESTful API, jQuery, jsp, Spring Boot,Eclipse}}{Nov 2023 }
          % \resumeItemListStart
          %   \resumeItem{Developed and integrated a text editor for live banking, enhancing email editing capabilities \& internal communication.}
          %   \resumeItem{Built an interactive editor system using Spring Boot, Java, jQuery, and REST, improving functionality and UX.}
          %   \resumeItem{Ensured seamless integration, real-time updates, and efficient backend interaction by applying OOP's  principles.}
          % \resumeItemListEnd 
    \resumeSubHeadingListEnd
\vspace{-15pt}

%-----------EDUCATION-----------
\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Bachelor of Engineering- Mumbai University}{Sep 2018 -- May 2022}
      {Rajiv Gandhi Institute of Technology}{8.24 CGPA}
  \resumeSubHeadingListEnd

%

%------RELEVANT COURSEWORK-------
\section{Relevant Coursework}
    %\resumeSubHeadingListStart
        \begin{multicols}{4}
            \begin{itemize}[itemsep=-5pt, parsep=3pt]
                \item\small Object-Oriented Programming
                \item AWS
                \item Java Programming
                \item System Design
                \item Spring Framework
                \item Structured Query Language
                \item Hibernate ORM
                \item Agile Methodologies
                \item Linux
            \end{itemize}
        \end{multicols}
        \vspace*{2.0\multicolsep}
    %\resumeSubHeadingListEnd

%-----------INVOLVEMENT---------------
\section{Achievement}
    \resumeSubHeadingListStart
        \resumeSubheading{LeetCode}{}{}{}
        \vspace{-15pt}
            \resumeItemListStart
                \resumeItem{Solved over 200+ problems on LeetCode, improving problem-solving skills in data structures and algorithms.}
                \resumeItem{Earned a 50-day streak badge, demonstrating consistency and dedication to coding practice.}
            \resumeItemListEnd
    \resumeSubHeadingListEnd



\end{document}
