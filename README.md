%-------------------------
% Resume in Latex
% Author : Syed Riyan
% Based off of: https://github.com/sb2nov/resume
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
\usepackage[english]{babel}
\usepackage{tabularx}
\usepackage{fontawesome5}
\usepackage{multicol}
\usepackage{graphicx}
\setlength{\multicolsep}{-3.0pt}
\setlength{\columnsep}{-1pt}
\input{glyphtounicode}

\RequirePackage{tikz}
\RequirePackage{xcolor}
\RequirePackage{fontawesome}
\usepackage{ragged2e}
\usepackage{indentfirst}
\usetikzlibrary{svg.path}


\definecolor{cvblue}{HTML}{0E5484}
\definecolor{black}{HTML}{130810}
\definecolor{darkcolor}{HTML}{0F4539}
\definecolor{cvgreen}{HTML}{3BD80D}
\definecolor{taggreen}{HTML}{00E278}
\definecolor{SlateGrey}{HTML}{2E2E2E}
\definecolor{LightGrey}{HTML}{666666}
\colorlet{name}{black}
\colorlet{tagline}{darkcolor}
\colorlet{heading}{darkcolor}
\colorlet{headingrule}{cvblue}
\colorlet{accent}{darkcolor}
\colorlet{emphasis}{SlateGrey}
\colorlet{body}{LightGrey}




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
}{}{0em}{}[\color{red}\titlerule \vspace{-5pt}]

%Ensure that generate pdf is machine readable/ATS parsable
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
      \textbf{\large#1} & \textbf{\small #2} \\
      \textit{\large#3} & \textit{\small #4} \\
      
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


\newcommand\sbullet[1][.5]{\mathbin{\vcenter{\hbox{\scalebox{#1}{$\bullet$}}}}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%


\begin{document}

%----------HEADING----------


\begin{center}
    {\Huge \scshape SYED RIYAN} \\
    \small \href{https://maps.app.goo.gl/2J4qERykctsbdA5g6}{\raisebox{-0.1\height}\faMapMarker\ \ {Zahirabad, Telangana}}
    \href{tel:+91 9390146275}{ \raisebox{-0.1\height}\faPhone\ \ {+91 9390146275} ~} \href{mailto:syedriyan.rk7@gmail.com}{\raisebox{-0.2\height}\faEnvelope\  \ {syedriyan.rk7@gmail.com}} ~ 
    \href{https://www.linkedin.com/in/syed-riyan-7a2303258/}{\raisebox{-0.2\height}\faLinkedinSquare\ \ {Syed Riyan}}  ~
    \href{https://github.com/syedriyansr7}{\raisebox{-0.2\height}\faGithub\ \ {Syed Riyan}} \\
    \vspace{1pt}
    \resumeItem{\large\textbf{Circuit \& Technology Enthusiast}} \\ \vspace{20pt}
   
    \vspace{-8pt}
\end{center}

\vspace{-12pt}

%-------------CAREER OBJECTIVE-------------
   
\section{CAREER OBJECTIVE}
\begin{justify}
    {\normalsize \quad{To Leverage my technical knowledge in Renewable energy and Power electronics in a dynamic organization, while gaining practical experience and contributing to impactful projects. I aim to grow both personally and professionally through teamwork, leadership and continuous learning, ultimately contributing to the organization's success.}}
\end{justify}
    
    %-----------PROGRAMMING SKILLS-----------
   
\section{SKILLS / TECHNICAL COMPETENCIES}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{\underline{\normalsize{\Large{Hard Skills}}}}\\ \textbf{\normalsize{Programming Languages:}}{ \normalsize{C, C++, Python, Latex.}} \\  
     \textbf{\normalsize{Software/Technologies:}}{\normalsize{ AUTOCAD, Arduino IDE, Kiel microvision, MATLAB, OrCAD Schematic, Adobe Photoshop, Canva.}} \\
     \textbf{\normalsize{Microsoft Office Tools:}}{\normalsize{ Power BI, Microsoft Word, Microsoft PowerPoint, Microsoft Excel.}} \\
     \textbf{\normalsize{Core Knowledge:}}{\normalsize{ Analog and Digital Electronics, Power Electronics, Electric Circuit Analysis, Power System Analysis, Control Systems, Embedded Systems, Microcontrollers.}} \\
\vspace{6pt}
     \textbf{\underline{\normalsize{\Large{Soft Skills}}}}\\ \textbf{\normalsize{Team Collaboration:}}{ \normalsize{Effective teamwork and shared responsibilities.}}\\
     \textbf{\normalsize{Adaptability:}}{ \normalsize{Flexible and open to change in new situations.}}\\
     \textbf{\normalsize{Problem Solving:}}{ \normalsize{Analyzing issues and developing effective solutions.}}\\
     \textbf{\normalsize{Creativity:}}{ \normalsize{Thinking outside the box to generate innovative ideas.}}\\
     \textbf{\normalsize{Leadership:}}{ \normalsize{Proven ability to lead in both sports and academic projects.\\
     \textbf{\normalsize{Attention to detail:}}{ \normalsize{Focused on accuracy and quality in your work, especially in technical projects.}}\\
}}\\
    }}
 \end{itemize}
 \vspace{-12pt}
%Projects
\section{PROJECTS}
    \vspace{-5pt}
    \resumeSubHeadingListStart
       \resumeProjectHeading
          {\href{https://drive.google.com/file/d/1JRsJP_zEyZaW0zPCbh_weH2_KCrp1fep/view?usp=sharing}{\textbf{\large{\underline{Home Automation Using IOT Cloud}}} \href{}{\raisebox{-0.1\height}\faExternalLink }} $|$ \large{\underline{IOT \& Blynk Technology}}}{September 2024}
          \resumeItemListStart
            \resumeItem{\normalsize{Enables remote control of home appliances via the internet for convenience.}}
            \resumeItem{\normalsize{Utilizes NodeMCU ESP8266 and Blynk app for smart home management.}}
            

          \resumeItemListEnd 
          \vspace{-4pt}
          
          
          
          
          \resumeProjectHeading
          {\href{https://drive.google.com/file/d/1HyC-ZHSQqimW5-ooBzSZvCs7RKclyVQt/view?usp=sharing}{\textbf{\large{\underline{Automatic Solar Tracking System}}} \href{Project Link}{\raisebox{-0.1\height}\faExternalLink }} $|$ \large{\underline{Arduino Microcontroller}}}{March 2024}
          \resumeItemListStart
            \resumeItem{\normalsize{Optimizes solar panel positioning to maximize energy absorption using sunlight tracking. }}
            \resumeItem{\normalsize{Utilizes Arduino for automated adjustments based on the sun's direction.}}
            
          \resumeItemListEnd
           \vspace{-4pt}
          
          \resumeProjectHeading
{\href{https://drive.google.com/file/d/1fMwQX1xi0LxjFzr3jFoRlVQeoUFXoydw/view?usp=sharing}{\textbf{\large{\underline{Bluetooth and Wi-Fi Controlled Led Board using Arduino UNO}}} \href{}{\raisebox{-0.1\height}\faExternalLink }} $|$ \large{\underline{Arduino UNO}}}{March 2021}
          \resumeItemListStart
            \resumeItem{\normalsize{Enables wireless control of an LED board using Bluetooth and Wi-Fi.}}
            \resumeItem{\normalsize{Utilizes Arduino UNO for connectivity with mobile devices.}}
            
          \resumeItemListEnd

 %---------------EDUCATION DETAILS-----------------
 \section{EDUCATION}
  \resumeSubHeadingListStart
    \resumeSubheading
      {B.E. \& B.E. Honours in Electrical \& Electronics Engineering}{Anticipated Graduation 2025}
      {Guru Nanak Dev Engineering College affiliated to VTU Belagavi }{Bidar, Karnataka, India}\\
      \vspace{6pt}
      {\normalsize\textbf $\sbullet[.75] \hspace{0.1cm}${Aggregate Percentage (Until 6th Sem.) - 81.5\%}}
           
      \resumeItemListEnd
  \resumeSubHeadingListEnd
  \vspace{-2pt}
    \resumeSubHeadingListStart
    \resumeSubheading
      {Diploma in Electrical and Electronics Engineering}{June 2018 -- June 2021}
      {Government Polytechnic College Zahirabad - SBTET Board Hyderabad }{Zahirabad, Telangana, India}\\
     \vspace{6pt}
     {\normalsize\textbf $\sbullet[.75] \hspace{0.1cm}${Percentage - 82.94\%}}
                  \resumeItemListEnd
     \resumeSubHeadingListEnd
      \resumeSubHeadingListStart
    \resumeSubheading
      {SSC/10th}{June 2006 -- March 2018}
      {Gandhi Memorial High School Zahirabad - SSC Board Telangana }{Zahirabad, Telangana, India}\\
        \vspace{6pt}
        {\normalsize\textbf $\sbullet[.75] \hspace{0.1cm}$ {Percentage - 83.6\%}}
              \resumeItemListEnd
  \resumeSubHeadingListEnd

%---------------CERTIFICATIONS------------
\section{CERTIFICATIONS}
$\sbullet[.75] \hspace{0.1cm}$ {\href{}{Certificate of Internship on Electric Vehicles -} {\textbf{Seventh Sense Talent Soluions} } \\
$\sbullet[.75] \hspace{0.1cm}$ {\href{}{Certificate of Internship on Softskills and C-Programming -} {\textbf{Seventh Sense Talent Soluions} } \\
$\sbullet[.75] \hspace{0.1cm}$ {{Basics of Microsoft Power BI -} {\textbf{Coursera} \\
$\sbullet[.75] \hspace{0.1cm}$ {\href{}{Google Data Analytics -} {\textbf{Coursera} } \\
$\sbullet[.75] \hspace{0.1cm}$ {\href{}{Advanced Python -} {\textbf{Udemy} } \\
$\sbullet[.75] \hspace{0.1cm}$ {\href{}{Advanced C - Programming -} {\textbf{Udemy} } \\

$\sbullet[.75] \hspace{0.1cm}$ {\href{}{Two days hands on workshop on ARDUINO }\\%{by {\textbf{Er.Vijay} }}   \\

$\sbullet[.75] \hspace{0.1cm}$ {\href{}{One day workshop on 3D printing }{by {\textbf{Er.Vijay} }} \\


 %-----------VOLUNTEER EXPERIENCE---------------
\section{VOLUNTEER EXPERIENCE}
$\sbullet[.75] \hspace{0.1cm}$ {\href{}{Core member of COSINE Association EEE department @ GNDEC.}} \\

$\sbullet[.75] \hspace{0.1cm}$ {\href{}{Member of Google Students Developers Club[GDSC] (2023-2025) @ GNDEC.}} \hspace{1.6cm} \\

$\sbullet[.75] \hspace{0.2cm}${\href{}{Member of IEEE students Chapter (2024-2025) @ GNDEC. }} \\

$\sbullet[.75] \hspace{0.1cm}$ {\href{}{Organising member for Two Days National Level Techno-Cultural Fest "GURU FEST 2023" @ GNDEC.}} \\

$\sbullet[.75] \hspace{0.1cm}$ {\href{}{Organising member for Two Days District Level Inter-Polytechnic Sports Meet "DLIPSGM 2019" @ Government Polytechnic Zahirabad.}} \\

 
  %-----------HONOURS AND AWARDS---------------
\section{HONOURS AND AWARDS}

$\sbullet[.75] \hspace{0.1cm}$ {\href{}{Participated in "SMART INDIA HACKATHON 2022" @GNDEC.}} \hspace{2.59cm} \\
$\sbullet[.75] \hspace{0.2cm}${\href{}{WON 1st Prize in QUIZ Competition held in VTU
"YUKTI 2024" National Level Cultural and Technical event held at
VTU Regional Centre Kalaburagi .}} \\
$\sbullet[.75] \hspace{0.2cm}${\href{} {Won the ‘100m Running’ competition in "DLIPSGM 2019" @ Govt. Polytechnic Zahirabad .}}\\
$\sbullet[.75] \hspace{0.1cm}$ {\href{}{Received a Letter of Appreciation from Principal of GNDEC for contributing in Sucessesful condution of "GURU FEST 2023" .}} \hspace{1.6cm} \\

%-------------HOBBIES AND INTRESTS-------------
 \section{HOBBIES AND INTRESTS}
 \begin{justify}
 \textbf{\normalsize{Graphic Designing:}}{\normalsize{ Passionate about creating visual content using software like Adobe Photoshop and Canva. I enjoy designing logos, posters, and social media graphics.
}}
\end{justify}  \\
\begin{justify}
\textbf{\normalsize{Circuit Design:}}{\normalsize{ Enthusiastic about designing and simulating electronic circuits using software tools such as OrCAD.
}} 
\end{justify}\\

%-------------PERSONAL DETAILS-------------
  \section{PERSONAL DETAILS}  
{\normalsize{DOB:}}{ \normalsize{October 28, 2002.}}\\
{\normalsize{Address:}}{ \normalsize{Moosa Nagar Colony, Zahirabad Mdl., Telangana.}}\\ 
{\normalsize{Maritial Status:}}{ \normalsize{Unmarried.}}\\
{\normalsize{Languages Known:}}{ \normalsize{English, Telugu, Urdu, Hindi.}}\\

%-------------DECLARATION-------------
 \section{DECLARATION}  
     {\normalsize{I hereby declare that all the facts given above are true and correct to the best of my knowledge.}
\end{document}
