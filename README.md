<!-- Write a HTML code to frame a table where title should we at left and URL video at right with the heading -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Assingment 1</title>
    <style>
        table{
            /* width: 100%; */
            border-collapse: collapse;
            text-align: center;
            color: rgb(24, 21, 21);
        }

        td, th{
                border: 1px solid black;
                padding: 5px;
        }
    </style>
</head>
<body>
   <table style="width: 100%;">
    
    <tr>
        <th>Title</th>
        <th>Video URL</th> 
    </tr>
    <tr>
        <td>Class ID and iframe | HTML in Hindi</td>
        <td><iframe width="560" height="315" src="https://www.youtube.com/embed/I7LrS1z_WNA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></td> 
    </tr>

    <tr>
    <td>List, inline and Block element</td>
        <td><iframe width="560" height="315" src="https://www.youtube.com/embed/MiJrcI4LXMA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></td>
    </tr>
    <tr>
    <td>Tables in HTML in HINDI</td>
        <td><iframe width="560" height="315" src="https://www.youtube.com/embed/d2Tb9hd9pHM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></td>
    </tr>
    <tr>
    <td>Links and Images with Map </td>
        <td style="width: 50%;"><iframe width="560" height="315" src="https://www.youtube.com/embed/T_ca5aO3WN0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></td>
    </tr>
    <tr>
    <td>Value of colors and CSS format</td>
        <td><iframe width="560" height="315" src="https://www.youtube.com/embed/AdmLG2xhdvM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></td>
    </tr>
    
   </table>
</body>
</html>
