\documentclass[11pt, letterpaper]{article}
\usepackage[utf8]{inputenc}
\pagestyle{empty} % Suppress page numbers
\usepackage[left=0.6 in,top=0.8in,right=0.6in,bottom=0.6in]{geometry} %margins
\usepackage{scrextend} % allows finer margin manipulation 
\usepackage[none]{hyphenat} % removes all hyphenation
\setlength{\parindent}{0pt} % turns off indentation
\usepackage{tgpagella} % palatino font - text only
\usepackage{enumitem} %for space between list items
\setlist[itemize]{noitemsep, topsep=0pt, partopsep=0pt}
\renewcommand\labelitemi{$\circ$} %bullet for list items 

\usepackage{bibentry} %for references
%\usepackage[dvipsnames]{xcolor} %for colors
\usepackage{hanging}
\usepackage{hyperref}
\usepackage{fontawesome}

\newenvironment{CVSection}{
\begin{addmargin}[2em]{0em}
\begin{samepage}}
{\end{samepage}
\end{addmargin}\bigskip}

\newcommand{\CVList}[2]{
\begin{samepage}
\begin{itemize}[leftmargin=*]
\item \textsl{#1}
\end{itemize}
\begin{addmargin}[2.5em]{0em}
#2
\end{addmargin}
\end{samepage}
}

\newcommand{\CVHeading}[1]{
\MakeUppercase{\bf #1}
\smallskip
\hrule
\medskip
}

% ---------------------------------------------------
\begin{document}
{\Huge\textbf{Joseph C. Mays}}\\\\
\faHome\hspace{2 mm}564 1st Ave, Apt 12C, New York, NY 10016\\
\faEnvelopeSquare\hspace{2.3 mm}\href{mailto:josephcmays+CV@gmail.com}{josephcmays@gmail.com}\\
\faPhone\hspace{2.4 mm}973.934.5264\\
\faGithub\hspace{2 mm}\href{https://github.com/joeymays}{github.com/joeymays}\\

\CVHeading{Education}
\begin{CVSection}
\textbf{New York University School of Medicine}, New York, NY \hfill August 2018--Present\\
PhD, Cell Biology\\
Cumulative GPA: 3.87
\end{CVSection}

\begin{CVSection}
\textbf{Colgate University}, Hamilton, NY \hfill May 2016\\
Bachelor of Arts, Molecular Biology (with honors) \& Classical Studies\\ 
Cumulative GPA: 3.59, Magna Cum Laude
\end{CVSection}

\CVHeading{Honors, Awards, \& Grants}
\begin{CVSection}
\begin{tabular}{r|l}
2019 & Genome Integrity Training Grant, NYU School of Medicine\\
2016 & NIDCD Director’s Award, NIH\\
2016 & Beta Beta Beta Biology Honor Society, Colgate University\\
2016 & Eta Sigma Phi Classics Honor Society, Colgate University\\
2016 & N.L. Andrews Prize for Excellence in the Classics, Colgate University\\
2013--2016 & Dean’s Award for Academic Excellence, Colgate University\\
2016 & James M. Maury M.D. Scholarship, Colgate University\\
2016 & Marion A. Cincotta Scholarship, Colgate University\\
2012--2015 & North Eastern Roofing Educational Foundation Scholarship, NERCA\\
2014 & Lila \& Curtiss Frank Scholarship, Colgate University
\end{tabular}
\end{CVSection}

\CVHeading{Research Experience}
\begin{CVSection}
\textbf{National Institute on Deafness and other Communication Disorders,\\National Institutes of Health}, Bethesda, MD\\
\textsl{Post-baccalaureate Fellow, Laboratory of Cochlear Development	\hfill July 2016--August 2018\\}
Mentors: Dr. Michael Kelly, PhD; Dr. Matthew Kelley, PhD
\begin{itemize}
\item Evaluated the role of histone acetylation in cell identity maintenance and fate plasticity in the\\ developing mammalian cochlea
\item Characterized cellular heterogeneity within the mammalian cochlea using several single-cell RNA sequencing platforms
\item Explored transcriptomes of mammalian pineal gland cells and their role in circadian rhythm regulation in collaboration with the Nat'l Institute of Child Health and Development
\item Applied computational analyses to evaluate and interpret high-dimensional sequencing data
\item Mentored undergraduate students in project management and laboratory techniques
\item Collaborated with several NIH labs to share single-cell genomics experience and skills
\item Managed a large colony of several transgenic mouse lines for use in experiments
\item Presented novel research at national and regional hearing research conferences
\end{itemize}
\end{CVSection}
\begin{CVSection}
\textbf{National Institute on Deafness and other Communication Disorders,\\National Institutes of Health}, Bethesda, MD\\
\textsl{Intern, Laboratory of Cochlear Development	\hfill June 2015--December 2015\\}
Mentors: Dr. Kathryn Ellis, PhD; Dr. Matthew Kelley, PhD
\begin{itemize}
\item Identified lineage relationships of cell types in the mammalian cochlea through clonal analysis
\item Analyzed gene expression in the cochlea using immunohistochemistry and confocal microscopy over several developmental time points
\item Engaged in biology coursework for the Colgate University-NIH off-campus study program
\end{itemize}
\end{CVSection}

\begin{CVSection}
\textbf{Colgate University}, Hamilton, NY\\
\textsl{Research Assistant, Department of Biology\hfill January 2014--May 2014\\}
Mentor: Dr. Douglas Guarneri, PhD
\begin{itemize}
\item Assisted Prof. Guarneri in continuing research on stress-induced gene expression in mice
\item Validated complex plasmid maps through restriction enzyme digestion
\item Implemented software solutions to provide virtual models of plasmids, restriction digests, \\and site-directed mutagenesis to aid future experimental designs
\end{itemize}
\end{CVSection}

\CVHeading{Employment Experience}
\begin{CVSection}
\textbf{Colgate University}, Hamilton, NY\\
\textsl{Technology Assistant, Classics Department\hfill  February--May 2016}
\begin{itemize}
\item Prepared and maintained presentation equipment for Prof. Ammerman’s weekly classes
\end{itemize}
\end{CVSection}
\begin{CVSection}
\textbf{MedLabs Diagnostics}, Cedar Knolls, NJ\\
\textsl{Intern, Department of Molecular Diagnostics\hfill June--August 2014}
\begin{itemize}
\item Performed amplification-based diagnostic assays to test samples for bacteria and parasites
\item Participated in diagnostic method comparison studies and method validations
\item Compiled and edited standard operating procedures for new diagnostic instruments and methods
\end{itemize}
\end{CVSection}
\begin{CVSection}
\textbf{Colgate University}, Hamilton, NY\\
\textsl{Lifeguard, Lineberry Natatorium \hfill January 2013--May 2015}
\end{CVSection}

\CVHeading{Leadership Experience}
\begin{CVSection}
\textbf{NYU School of Medicine}, New York, NY\\
\textsl{Secretary, Sackler Institute Student Council	\hfill Spring 2019--Present}
\begin{itemize}
\item Manage and execute ongoing council projects
\item Coordinate orientation and recruitment events for new and prospective students
\item Organize meetings and resources for council members
\end{itemize}
\end{CVSection}
\begin{CVSection}
\textbf{Colgate University}, Hamilton, NY\\
\textsl{President, Colgate Classics Society	\hfill Spring 2015, Spring 2016}
\begin{itemize}
\item Coordinated outreach events with Classics Department faculty to broaden interest in the department and its course offerings
\item Communicated and collaborated with society members during bi-monthly meetings
\item Managed a semester budget for team-building and outreach events
\end{itemize}
\end{CVSection}

\CVHeading{Teaching Experience}
\begin{CVSection}
\textbf{National Institute on Deafness and other Communication Disorders,\\ National Institutes of Health}, Bethesda, MD\\
\textsl{Instructor, EARssentials Mouse Cochlea Dissection Workshop\hfill July 2016, July 2017}
\begin{itemize}
\item Co-taught laboratory workshop on neonatal mouse cochlea micro-dissection
\end{itemize}
\end{CVSection}

\CVHeading{Oral Presentations}
\begin{CVSection}
\CVList{Exploration of a multicellular phenotype in cochlear tissue using single-cell RNA-sequencing methods.}{NIDCD Trainee Talks, NIH, June 2017.}
\CVList{Drop-Seq as a low-cost, high-throughput method for single-cell gene expression profiling of cochlear cells.}{NIDCD Division of Intramural Research Retreat, NIH, May 2017.}
\CVList{Using Seurat and Monocle for analysis of single-cell RNA-sequencing data.}{NIAMS Bioinformatics Interest Group, NIH, April 2017.}
\CVList{Lineage tracing in the developing mammalian cochlea.}{Colgate University Honors Talks, April 2016.}
\CVList{Doing science in college. \textnormal{(Invited Speaker)}}{West Milford High School Science Honor Society, March 2016.}
\end{CVSection}

\CVHeading{Poster Presentations}
\begin{CVSection}
\CVList{Single-cell pineal gland neuro-transcriptomic analysis reveals cell type-specific day/night changes.}{NICHD Division of Intramural Research Retreat, NIH, September 2017.}
\CVList{Drop-seq as a low-cost, high-throughput method for single-cell gene expression profiling of cochlear cells.}{Post-baccalaureate Fellow Poster Day, NIH, May 2017.}
\CVList{Demonstration of analysis of high-throughput single cell RNA-Seq data using open-source R packages.}{Pi Day, NIH, March 2017.}
\CVList{Drop-seq as a low-cost, high-throughput method for single-cell gene expression profiling of cochlear cells.}{Association for Research in Otolaryngology Mid-Winter Meeting, February 2017.}
\CVList{Lineage tracing in the developing mammalian cochlea.}{Summer Student Poster Day, NIH, August 2015.}
\end{CVSection}

\CVHeading{Other Conferences Attended}
\begin{CVSection}
\CVList{Next-Generation Genomics}{New York University, New York, NY, August 2019.}
\CVList{Eastern Auditory Retreat}{Georgetown University, Washington, DC, June 2017.}
\CVList{Single Cell Analysis Investigators Meeting}{National Institutes of Health, Bethesda, MD, June 2017.}
\end{CVSection}

\nobibliography{pub}
\bibliographystyle{acm}

\CVHeading{Publications}
\begin{CVSection}
%\bibentry{Mays_2018}


\textbf{Mays JC}, Kelly MC, Coon SL, Holtzclaw L, Rath MF, Kelley MW, and Klein DC. (2018) Single-cell RNA sequencing of the mammalian pineal gland identifies two pinealocyte subtypes and cell type-specific daily patterns of gene expression. PLOS ONE 13(10): e0205883.\\
\hspace{2 in}\href{https://www.ncbi.nlm.nih.gov/pubmed/30347410}{\faFileTextO\hspace{1mm}PubMed 30347410}
\hspace{2mm}\href{https://github.com/joeymays/PinealGland_SingleCell}{\faCode\hspace{1mm}Codebook}\medskip
%\hspace{2mm}\color{blue}\faCode\hspace{1mm}\href{https://github.com/joeymays/PinealGland_SingleCell}{Codebook}
%color version^

Coon SL, Fu C, Hartley S, Holtzclaw L, \textbf{Mays JC}, Kelly MC, Kelley MW, Mullikin JC, Rath MF, Savastano LE and Klein DC. (2019) Single Cell Sequencing of the Pineal Gland: The Next Chapter. Front. Endocrinol. 10:590.
\medskip

Kolla L, Kelly MC, Mann ZF, Ellis K, Lemons A, Palermo AT, So KS, \textbf{Mays JC}, Orvis J, Burns JC, Hertzano R, Driver EC, and Kelley MW. (2019) Characterization of cochlear hair cell development at the single cell level.
(Submitted to \textsl{Nature Communications}.)
\end{CVSection}
\end{document}
