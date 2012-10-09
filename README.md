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

    <!-- Start of StatCounter Code for Default Guide -->
    <script type="text/javascript">
    var sc_project=8216663; 
    var sc_invisible=1; 
    var sc_security="a871624d"; 
    var sc_https=1; 
    var scJsHost = (("https:" == document.location.protocol) ?
    "https://secure." : "http://www.");
    document.write("<sc"+"ript type='text/javascript' src='" +
    scJsHost +
    "statcounter.com/counter/counter.js'></"+"script>");</script>
    <noscript><div class="statcounter"><a title="web stats"
    href="http://statcounter.com/" target="_blank"><img
    class="statcounter"
    src="https://c.statcounter.com/8216663/0/a871624d/1/"
    alt="web stats"></a></div></noscript>
    <!-- End of StatCounter Code for Default Guide -->