# 4punkte.github.io
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Frameset//EN"
   "http://www.w3.org/TR/html4/frameset.dtd">
<html>
	<head>
		
		<title>17.10.26</title>
		<link rel="shortcut icon" href="4punkte-yed-grafik-ico2.ico" />	
		
		<base target="frame2">
		<!-- Schlagworte -->
		<meta name="keywords" lang="de" content="Website4Punkte">
		<meta name="keywords" lang="en-us" content="home">
		<meta name="keywords" lang="en" content="">
		<!-- ... andere Angaben im Dateikopf ... -->
		<!-- kurze Beshreibung -->
		<meta name="description" content="HomeWebSite">
		<meta name="robots" content="noindex|nofollow">
	</head>

<!--  Menu, Startseite, CatSeite */framset bei rechten Frame -->
<frameset cols="10%,*,20%" border="0">  
	   <frame src="./menue.html" NAME="frame1" SCROLLING="auto" NORESIZE />
			<frameset border="0">
				<frame src="{{ page.start_menue }}" NAME="frame2" SCROLLING="auto" NORESIZE />
			</frameset>
			<frameset border="0">
				<frame src="{{ page.start_rechts }}" NAME="rechts" SCROLLING="auto" NORESIZE /> 
			</frameset>
</frameset>

<!-- Startseite, Menu/CatSeite 
<frameset cols="*,20%" border="0">  
			<frameset border="0">
				<frame src="{{ page.start_menue }}" NAME="frame2" SCROLLING="auto" NORESIZE />
			</frameset>
			<frameset border="0">
				<frame src="{{ page.start_rechts }}" NAME="rechts" SCROLLING="auto" NORESIZE />
			</frameset>
</frameset>
-->

<noframes>
<body> <p>Kurzbeschreibung der Seite Suchmaschienen</p> </body>
</noframes>
<!-- 
	<frameset rows="15%,*" border="0">	
		<frame src="./m0oben.html" name="oben">
		<frameset cols="15%,*" border="0">
			   <frame src="./m0menue.html" NAME="frame1" SCROLLING="auto" NORESIZE >
			   <frame src="./h0home.html" NAME="frame2" SCROLLING="auto" NORESIZE>
				<noframes>
					<body>
					<p><a href="./m0menue.html">Navigation</a> <a href="./h0home.html">Daten</a></p>
					</body>
				</noframes>
		</frameset>
	</frameset>
-->
</html>


