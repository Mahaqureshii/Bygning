<!DOCTYPE html>
<head>
    <style>
        table.striped > tbody > tr:nth-child(odd) {
            background-color: #f6f5f4;
        }
        table.striped > tbody > tr:nth-child(even) {
            background-color: #bdd4de;
        }          
        th{
            text-align: center;
            padding: 7px 14px;
            color: white;
            background-color: #3f4259
        }
        h1{
            background-color: #3f5765;
            padding: 2.5rem;
            width: 564px;
            font-family: Arial, Helvetica, sans-serif;
            color: white;
            border: 2px solid black;
        }
        td{
            font-family: Georgia, 'Times New Roman', Times, serif;
            border: 2px solid white;
        }
        table{
            border: 2px solid black;
            border-collapse: collapse;
            border-style: solid;
            border-color: #bdd4de;
            border-width: 10px;
            padding: 7px 14px solid black;
        }
        section{
            display: flex;
            height: 70px;
            width: 67px;
            border-top: 40px solid #3f3f3f;
            border: 2px solid black;
        }
        body {
            background-color: #404040;
        }
        img {
            width: 215px;
            border-style: solid;
            border-color: black;
            border-width: 2px;
            height: 80vh;
            object-fit: cover;
        }
        .one div {
            height: 65vh;
            width: 39vh;
            position: relative;
            right: 50px;
            display: flex;
            background-size: cover;
            background-position: center;
        }
        .two div {
            height: 65vh;
            width: 39vh;
            position: relative;
            right: 48px;
            display: flex;
            background-size: cover;
            background-position: center;
        }
        .three div {
            height: 65vh;
            width: 39vh;
            position: relative;
            right: 82px;
            display: flex;
            background-size: cover;
            background-position: center;
        }
    </style>
</head>
<body>
    <table border="2" class="striped">
        <thead>
            <h1>Verdens tre høyeste skyskrapere</h1>
            <tr>
                <th>Skyskraper</th>
                <th>Høyde</th>
                <th>By</th>
                <th>Land</th>
                <th>Byggeår</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Burj Khalifa</td>
                <td>828 m</td>
                <td>Dubai</td>
                <td>De forente arabiske emirater </td>
                <td>2009</td>
            </tr>
            <tr>
                <td>Shanghai Tower</td>
                <td>632 m</td>
                <td>Shanghai</td>
                <td>Kina</td>
                <td>2014</td>
            </tr>
            <tr>
                <td>Makkah Royal Clock Tower </td>
                <td>601 m</td>
                <td>Mekkah</td>
                <td>Saudi-Arabia</td>
                <td>2011</td>
            </tr>
        </tbody>
    </table>
    <section>
        <article class="one">
            <a href="https://snl.no/Burj_Khalifa">
                <div>

                </div>
            </a>
        </article>
        <article class="two">
            <a href="https://en.wikipedia.org/wiki/Shanghai_Tower">
                <div>
                    
                </div>
            </a>
        </article>
        <article class="three">
            <a href="https://en.wikipedia.org/wiki/Abraj_Al_Bait">
                <div>
                    
                </div>
            </a>
        </article>
    </section>
</body>

<section>
    <img src="burj_stor.jpg">
    <img src="Shanghai_stor.jpg">
    <img src="Makkah_stor.jpg">
</section>
