# CSS-9
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>CSS基本样式习题9</title>
    <style>
        .table{
            width: 600px;
            margin: 0 auto;
        }
        .table>table{
            margin-top: 30px;
        }
        .manifest{
            border-collapse: collapse;
            border-spacing: 0;
            width: 100%;
            border:1px solid #ccc;
        }
        .manifest tr{
            border-bottom: 1px solid #ddd;
            text-align: left;
        }
        .manifest tr:nth-child(even){
            background-color: #f1f1f1;
        }
        .manifest th{
            color:#fff;
            background-color: #4CAF50;
            padding:8px 8px;
            font-weight:bold;
        }
        .manifest td{
            padding:8px 8px;
        }
        .manifest.twice{
            border:none;
        }
        .manifest.twice th{
            background-color: #fff;
            color:#000;
        }
    </style>
</head>
<body>
    <div class="table">
        <table class="manifest">
            <tbody>
                <tr>
                    <th>First Name</th>
                    <th>Last Name</th>
                    <th>Points</th>
                </tr>
                <tr>
                    <td>Jill</td>
                    <td>Smith</td>
                    <td>50</td>
                </tr>
                <tr>
                    <td>Eve</td>
                    <td>Jackson</td>
                    <td>94</td>
                </tr>
                <tr>
                    <td>Adam</td>
                    <td>Johnson</td>
                    <td>67</td>
                </tr>
                <tr>
                    <td>Bo</td>
                    <td>Nilsson</td>
                    <td>50</td>
                </tr>
                <tr>
                    <td>Mike</td>
                    <td>Ross</td>
                    <td>35</td>
                </tr>
            </tbody>
        </table>
        <table class="manifest twice">
            <tbody>
                <tr>
                    <th>First Name</th>
                    <th>Last Name</th>
                    <th>Points</th>
                </tr>
                <tr>
                    <td>Jill</td>
                    <td>Smith</td>
                    <td>50</td>
                </tr>
                <tr>
                    <td>Eve</td>
                    <td>Jackson</td>
                    <td>94</td>
                </tr>
                <tr>
                    <td>Adam</td>
                    <td>Johnson</td>
                    <td>67</td>
                </tr>
                <tr>
                    <td>Bo</td>
                    <td>Nilsson</td>
                    <td>50</td>
                </tr>
                <tr>
                    <td>Mike</td>
                    <td>Ross</td>
                    <td>35</td>
                </tr>
            </tbody>
        </table>
    </div>
</body>
</html>
```
