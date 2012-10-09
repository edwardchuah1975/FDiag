FDiag
=====

FDiag is a log-analysis toolkit that processes cluster system logs to generate event patterns for diagnosis of the 
sources and causes of recurrent system failures.  When given a symptom event, FDiag extracts message templates from 
the logs (syslogs, rationalized logs by J.Hammond et. al., Bluegene/L logs, Cray-XT logs), identifies statistical 
correlations between the given symptom event and the message templates, and generates sequences of events associated 
with a given terminal event.

Earlier versions of FDiag were developed as part of an international collaboration between the Institute of High 
Performance Computing (IHPC), the University of Texas at Austin, the Texas Advanced Computing Center (TACC), and 
the A*Star Computational Resource Centre (ACRC).  The source of the earlier version can be obtained from this webpage: 
http://software.ihpc.a-star.edu.sg/projects/FDiag/FDiag.php .  The current as well as future versions of FDiag will be 
hosted here on Github.com .

FDiag is a living toolkit for which there are several plans to extend FDiag significantly.  If you are interested in 
the development and/or use of FDiag, please contact me by email to discuss a possible course of collaboration.

Edward Chuah (email: edwardchuah@acm.org)

https://gist.github.com/03e2bbab89b5b4fc74b0