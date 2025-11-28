# Score-Remark-Engine

<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Score-Remark-Engine</title>
</head>

<style>
    h1 {
        text-align: center;
        border: 5px solid black;
        width: 50%;
        border-radius: 10px;
        margin: auto;
    }
</style>

<body>
    <script>
        let num = + prompt('Enter your marks')

        if (isNaN(num)) {
            document.write('<h1><b> Enter Only Numbers <b></h1> ')
        }

        else if (num < 0 || num > 100) {
            document.write('<h1><b> Enter The Numbers Between 0 - 100 </b></h1>')
        }


        else if (num >= 90) {
            document.write('<h1><b> YOUR GRADE IS A+ (EXCELLENT) </b></h1>')
        }

        else if (num >= 80) {
            document.write('<h1><b> YOUR GRADE IS A (GREAT) </b></h1>')
        }

        else if (num >= 70) {
            document.write('<h1><b> YOUR GRADE IS B (GOOD) </b></h1>')
        }

        else if (num >= 60) {
            document.write('<h1><b> YOUR GRADE IS C (AVERAGE) </b></h1>')
        }

        else if (num >= 50) {
            document.write('<h1><b> YOUR GRADE IS D (NEEDS IMPROVEMENT) </b></h1>')
        }

        else {
            document.write('<h1><b> YOUR GRADE IS F (FAIL) </b></h1>')
        }
    </script>
</body>

</html>
