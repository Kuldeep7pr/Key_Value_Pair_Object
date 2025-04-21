<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Key-Value Pair Object</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.5/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-SgOJa3DmI69IUzQ2PVdRZhwQ+dy64/BUtbMJw1MZ8t5HZApcHrRKUc4W0kG879m7" crossorigin="anonymous" />
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.5/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-k6d4wzSIapyDyv1kpU366/PK5hCdSbCRGRCMv+eplOQJWyd1fbcAu9OCUj5zNLiq"
        crossorigin="anonymous"></script>
</head>

<body>

    <h1 class="text-primary fs-3 text-center mt-3 text-capitalize">Key-Value Pair Object</h1>
    <hr>
    <div id="output" class="border border-dark m-auto w-25 text-center p-2 fs-4 rounded-2">sdvsvsdv</div>
</body>

<script>

    let result = {
        "mohan": 54,
        "Khushi": 45,
        "Kuldeep": 100,
        "Vishal sir": 0.00
    }
    let output = '';


    for (let name in result) {
        let mark = result[name];
        output += `The ${name} has:- ${mark}.<br>`
        console.log();
    }

    document.getElementById('output').innerHTML = output;
</script>

</html>
