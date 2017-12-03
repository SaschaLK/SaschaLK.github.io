<html>
    <body>
        <div id="projects_navbar">
            <ul>
                <li><a href="#" id="mediTech">MediTech</a></li>
                <li><a href="#" id="casualTuna">IGJam #11 Casual Tuna</a></li>
                <li><a href="#" id="veiledNight">IGJam #12 Veiled Night</a></li>
                <li><a href="#" id="warCouncil">War Council</a></li>
                <li><a href="#" id="miningMan">Mining Man - VR</a></li>
            </ul>
        </div>
        <div id="mediTechResult">
            MeditTech has loaded
        </div>
        <script src="http://code.jquery.com/jquery-latest.min.js" type="text/javascript"></script>
        <script>
            &("#mediTech").on("click", funciont(){
                $("#mediTechResult").load("content.html");
                });
        </script>
    </body>
</html>