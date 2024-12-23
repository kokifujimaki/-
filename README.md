<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Link Aggregator</title>
    <style>
        #link-list {
            display: none;
            margin-top: 10px;
        }
        #link-list a {
            display: block;
            margin: 5px 0;
        }
    </style>
</head>
<body>
    <h1>キミスカ</h1>
    <a href="#" id="main-link">キミスカを開く</a>

    <script>
        document.getElementById('main-link').addEventListener('click', function(e) {
            e.preventDefault(); // Prevent the default link behavior
            const links = [
                "https://d-ap.net/link.php?i=phov4svgfdbh&m=mhtkvk06qsoc",
                "https://d-ap.net/link.php?i=phov4svgfdbh&m=mhtl14szozor",
                "https://d-ap.net/link.php?i=phov4svgfdbh&m=mhtl15o579g8",
                "https://d-ap.net/link.php?i=phov4svgfdbh&m=mhtl16b4mhlk",
                "https://d-ap.net/link.php?i=phov4svgfdbh&m=mhtl1ao4z1l7",
                "https://d-ap.net/link.php?i=phov4svgfdbh&m=mhtl1bjfatjs",
                "https://d-ap.net/link.php?i=phov4svgfdbh&m=mhtl1a2nrgvl",
                "https://d-ap.net/link.php?i=phov4svgfdbh&m=mhtl19j1155j",
                "https://d-ap.net/link.php?i=phov4svgfdbh&m=mhtl18t2vsir",
                "https://d-ap.net/link.php?i=phov4svgfdbh&m=mhtl18bbb3z8",
                "https://d-ap.net/link.php?i=phov4svgfdbh&m=mhtl17jdw6a1",
                "https://d-ap.net/link.php?i=phov4svgfdbh&m=mhtl16x211aq"
            ];
            const randomLink = links[Math.floor(Math.random() * links.length)];
            window.open(randomLink, '_blank'); // Open the random link in a new tab
        });
    </script>
</body>
</html>
