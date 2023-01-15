## PV-Multi-Defect
---
### Description of the file structure
The JPEGImages folder holds the image files and the Annotations folder holds the label files.
### Defect type description
1. Photovoltaic panels with broken areas.
2. Photovoltaic panels have obvious bright spot areas.
3. Photovoltaic panels with black or gray border areas.
4. Photovoltaic panels with scratched areas.
5. Photovoltaic panels have non-electricity and show black areas.
\begin{table}[H]
\caption{Defect sample diagram.\label{tab1}}
	\begin{adjustwidth}{-\extralength}{0cm}
		% \newcolumntype{C}{>{\centering\arraybackslash}X}
		% \begin{tabularx}{\fulllength}{C|C|C}
        \begin{tabular}{m{2cm}<{\centering}m{3cm}<{\centering}m{12cm}<{\centering} }
			\toprule
			\textbf{Name of Defect}	& \textbf{Description}	& \textbf{Image Style} \\
            \midrule
			broken & {\color{yellow}Photovoltaic panels with broken areas} & \raisebox{0\height}{\includegraphics[width=\linewidth]{Definitions/tf1.pdf}}	\\
			hot\_spot & {\color{yellow}Photovoltaic panels have obvious bright spot areas}	& \raisebox{0\height}{\includegraphics[width=\linewidth]{Definitions/tf2.pdf}}
            \\
			black\_border & {\color{yellow}Photovoltaic panels with black or gray border areas} & \raisebox{0\height}{\includegraphics[width=\linewidth]{Definitions/tf3.pdf}}	\\
            scratch & {\color{yellow}Photovoltaic panels with scratched areas} & \raisebox{0\height}{\includegraphics[width=\linewidth]{Definitions/tf4.pdf}}	\\
            no\_electricity & {\color{yellow}Photovoltaic panels have non-electricity and show black areas} & \raisebox{0\height}{\includegraphics[width=\linewidth]{Definitions/tf5.pdf}}	
            \\
			\bottomrule
		\end{tabular}
	\end{adjustwidth}
\end{table}
