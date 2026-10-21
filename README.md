\documentclass[10pt, a4paper]{article}

% ---------- Packages ----------
\usepackage[top=0.7cm, bottom=0.5cm, left=1.4cm, right=1.4cm]{geometry}
\usepackage[T1]{fontenc}
\usepackage[utf8]{inputenc}
\usepackage{lmodern}
\usepackage{titlesec}
\usepackage{enumitem}
\usepackage{graphicx}
\usepackage{fontawesome5}
\usepackage[dvipsnames]{xcolor}
\definecolor{primaryColor}{RGB}{0, 79, 144}
\usepackage[
    pdftitle={CV Souhir Guedda},
    pdfauthor={Souhir Guedda},
    colorlinks=true,
    urlcolor=black,
    linkcolor=black
]{hyperref}

% Texte lisible par les logiciels ATS
\input{glyphtounicode}
\pdfgentounicode=1

\pagestyle{empty}
\setlength{\parindent}{0pt}
\setlength{\parskip}{0pt}

% ---------- Taille du texte ----------
% Si le CV dépasse une page, remplace 10pt/11pt par 9.5pt/11pt
\renewcommand{\normalsize}{\fontsize{10pt}{11pt}\selectfont}

% ---------- Titres de sections (style Farah) ----------
\titleformat{\section}
    {\bfseries\normalsize\color{primaryColor}}
    {}{0pt}
    {}
    [\vspace{0pt}{\color{primaryColor}\titlerule[1.5pt]}]
% \titlespacing{\section}{gauche}{espace avant le titre}{espace après la ligne bleue}
\titlespacing{\section}{0pt}{4pt}{3pt}

% ---------- Listes ----------
\setlist[itemize]{leftmargin=14pt, itemsep=0pt, topsep=1pt, parsep=0pt, partopsep=0pt, label={\small$\circ$}}

% ---------- Commandes utiles ----------
% \entry{Organisme}{Lieu}{Type}{Dates}
\newcommand{\entry}[4]{\noindent{\color{primaryColor}\textbf{#1}}, #2 -- \textit{#3}\hfill\textit{#4}\par}

\begin{document}
\normalsize

% ---------- En-tête avec photo ----------
\begin{minipage}[c]{0.20\textwidth}
    % Mets ta photo dans le même dossier sous le nom photo.png
    \IfFileExists{photo.png}{\includegraphics[width=\textwidth, height=3.4cm, keepaspectratio]{photo.png}}{}
\end{minipage}%
\hfill
\begin{minipage}[c]{0.76\textwidth}
    \centering
    {\fontsize{22pt}{24pt}\selectfont\textbf{Souhir GUEDDA}}\\[3pt]
    {\large\color{primaryColor}\textbf{\textit{Ingénieure en Génie Logiciel}}}\\[5pt]
    \normalsize
    \mbox{{\footnotesize\faMapMarker*}\hspace{0.15cm}Bizerte, Tunisie}\hspace{0.4cm}
    \mbox{\href{tel:+21658103576}{{\footnotesize\faPhone*}\hspace{0.15cm}+216 58 103 576}}\\[2pt]
    \mbox{\href{mailto:souhirguedda960@gmail.com}{{\footnotesize\faEnvelope[regular]}\hspace{0.15cm}souhirguedda960@gmail.com}}\hspace{0.4cm}
    \mbox{\href{https://www.linkedin.com/in/souhir-guedda-51425a306/}{{\footnotesize\faLinkedinIn}\hspace{0.15cm}Souhir Guedda}}\hspace{0.4cm}
    \mbox{\href{https://github.com/Souhir29}{{\footnotesize\faGithub}\hspace{0.15cm}Souhir29}}
\end{minipage}

\vspace{2pt}

% ---------- Profil ----------
\section{PROFIL}
Ingénieure en Génie Logiciel, passionnée par la QA automation engineering et l'intelligence artificielle. Curieuse, rigoureuse et dotée d'un bon esprit d'analyse, je souhaite contribuer à des projets innovants et intégrer une entreprise en CDI en tant qu'ingénieure QA automation ou ingénieure IA.

% ---------- Expérience professionnelle ----------
\section{EXPÉRIENCE PROFESSIONNELLE}

\entry{COFICAB Group}{Tunis}{Projet de Fin d'Études}{Fév. – Août 2026}
\begin{itemize}
    \item Développement de tests de performance et de stabilité automatisés avec Playwright, avec collecte des métriques SAP et tableau de bord en temps réel.
    \item Mise en place d'un suivi des privilèges utilisateurs et de l'état des comptes SAP, avec détection des utilisateurs anormaux par Isolation Forest.
    \item Mise en place d'un assistant IA basé sur une architecture RAG.
    \item \textit{\textbf{Technologies :} Python, Playwright, Apache JMeter, scikit-learn, TypeScript, Next.js, React, SQLite, API Groq}
\end{itemize}

\vspace{2pt}
\entry{MIC}{Bizerte}{Stage d'été}{Juil. – Août 2025}
\begin{itemize}
    \item Conception et développement d'une application de détection et de reconnaissance faciale en temps réel.
    \item \textit{\textbf{Technologies :} Python, OpenCV, Mediapipe, DeepFace, Tkinter}
\end{itemize}

\vspace{2pt}
\entry{TPEG}{Bizerte}{Stage de fin d'études}{Fév. – Mai 2023}
\begin{itemize}
    \item Rénovation du système de commande d'une machine TKSM avec un automate Siemens S7-1200 : conception des schémas électriques et programmation en Ladder.
    \item Développement d'une interface homme-machine de supervision, installation et câblage des actionneurs et capteurs.
    \item \textit{\textbf{Technologies :} Automate Siemens, TIA Portal, WinCC Runtime, WinRelais, Win Armoire}
\end{itemize}

\vspace{2pt}
\entry{CRJ}{Bizerte}{Stage de perfectionnement}{Janv. – Fév. 2022}
\begin{itemize}
    \item Analyse et diagnostic d'une armoire électrique existante avec recommandations d'amélioration, et étude technique de la protection électrique (disjoncteurs, câblage).
    \item Développement d'une solution d'automatisation avec automate Siemens : conception GRAFCET et programmation en Ladder pour commander l'éclairage, les machines et les horaires de travail.
    \item \textit{\textbf{Technologies :} Automate Siemens, Ecodial, TIA Portal}
\end{itemize}

\vspace{2pt}
\entry{CRJ}{Bizerte}{Stage d'initiation}{Juil. – Août 2021}
\begin{itemize}
    \item Rendu d'observations sur les conditions de travail et les pratiques en vigueur.
\end{itemize}

% ---------- Formation (style Farah) ----------
\section{FORMATION}
\noindent\textbf{Institut Supérieur des Arts Multimédia de la Manouba (ISAMM)}\par
\noindent\textit{Cycle Ingénieur en Informatique}\hfill\textit{2026}\par
\vspace{2pt}
\noindent\textbf{Institut Supérieur des Études Technologiques de Bizerte (ISETB)}\par
\noindent\textit{1\textsuperscript{re} année Master Robotique avancée et Intelligence artificielle}\hfill\textit{2024}\par
\noindent\textit{Licence en Génie électrique, spécialité Automatisme et Informatique industrielle}\hfill\textit{2023}\par
\vspace{2pt}
\noindent\textbf{Lycée Mohamed Ali Annabi, Ras Jebel}\par
\noindent\textit{Baccalauréat Sciences techniques}\hfill\textit{2020}\par

% ---------- Projets académiques ----------
\section{PROJETS ACADÉMIQUES}
\noindent\textbf{Assistant IA interactif -- Reconnaissance de gestes \& IA générative} \hspace{0.2cm} \textit{Reconnaissance de gestes par webcam et réponse en langage naturel avec un LLM.\\ Technologies : Python, Streamlit, OpenCV, MediaPipe, Google Gemini}\par
\vspace{2pt}
\noindent\textbf{Classification d'images avec ResNet} \hspace{0.2cm} \textit{Entraînement d'un modèle ResNet pour la classification d'images.\\ Technologies : PyTorch, Python}\par

% ---------- Compétences ----------
\section{COMPÉTENCES}
\noindent\textbf{Tests UI Web :} Playwright, Selenium, Robot Framework\par
\noindent\textbf{Tests d'API :} Apache JMeter\par
\noindent\textbf{Langages :} Python, TypeScript\par
\noindent\textbf{Frameworks / Bibliothèques :} Next.js, React, Tailwind CSS, Streamlit, Tkinter\par
\noindent\textbf{IA / Machine Learning :} scikit-learn, PyTorch, OpenCV, MediaPipe, DeepFace, Isolation Forest, RAG, LLM (Gemini, Groq)\par
\noindent\textbf{Bases de données :} SQLite\par
\noindent\textbf{Automatisation industrielle :} Automate Siemens, TIA Portal, WinCC Runtime, WinRelais, Win Armoire, Ecodial \par

% ---------- Certifications ----------
\section{CERTIFICATIONS}
\noindent Certificate of Attendance -- AI \& Computer Vision \quad|\quad Azure AI Fundamentals \quad|\quad Certificat Voltaire\par
\noindent CCNA1, CCNA2 \par

% ---------- Langues ----------
\section{LANGUES}
\noindent\textbf{Arabe :} Langue maternelle \quad \textbf{Français :} Courant \quad \textbf{Anglais :} Intermédiaire\par

\end{document}
