<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ash / home</title>
    <script src="https://d3js.org/d3.v7.min.js"></script>
    <style>
        body { margin: 0; overflow: hidden; background-color: black; }
        .center-container {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            text-align: center;
            z-index: 10;
        }
        .button-container {
            margin-top: 20px;
            background-color: rgba(0, 0, 0, 0.5);
            padding: 5px;
            border-radius: 10px;
            display: inline-block;
        }
        .button {
            width: 40px;
            height: 40px;
            cursor: pointer;
            margin: 5px;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <svg id="space"></svg>
    <div class="center-container">
        <div id="text-container"></div>
        <div class="button-container">
            <a href="https://github.com/opaeoh" target="_blank">
                <img src="https://cdn.pixabay.com/photo/2022/01/30/13/33/github-6980894_1280.png" alt="Button 1" class="button">
            </a>
            <a href="https://x.com/opaeoh" target="_blank">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQatdy5z0N7MCb3l46oxDIrSq96-3FHCA8UOQ&s" alt="Button 2" class="button">
            </a>
        </div>
    </div>

    <script>
        const width = window.innerWidth;
        const height = window.innerHeight;
        const numStars = 500;

        const svg = d3.select("#space")
            .attr("width", width)
            .attr("height", height);

        // Create stars
        const stars = d3.range(numStars).map(() => ({
            x: Math.random() * width,
            y: Math.random() * height,
            z: Math.random() * width,
            r: Math.random() * 2 + 1
        }));

        const starGroup = svg.append("g");

        starGroup.selectAll("circle")
            .data(stars)
            .enter()
            .append("circle")
            .attr("cx", d => d.x)
            .attr("cy", d => d.y)
            .attr("r", d => d.r)
            .attr("fill", "white");

        // Add text and background
        const textContainer = d3.select("#text-container");

        textContainer.append("div")
            .style("background-color", "rgba(0, 0, 0, 0.5)")
            .style("padding", "20px")
            .style("border-radius", "10px")
            .html("<h1 style='font-size: 48px; color: white; margin: 0;'>ASH</h1>" +
                  "<p style='font-size: 24px; color: white; margin: 10px 0 0;'>Coder / AI-ML Dude . Working on <b><i>nograd</i></b></p>");

        // Animate stars
        function animateStars() {
            starGroup.selectAll("circle")
                .attr("cx", function(d) {
                    d.z -= 5;
                    if (d.z <= 0) {
                        d.z = width;
                        d.x = Math.random() * width;
                        d.y = Math.random() * height;
                    }
                    const scale = width / (width + d.z);
                    return (d.x - width / 2) * scale + width / 2;
                })
                .attr("cy", function(d) {
                    const scale = width / (width + d.z);
                    return (d.y - height / 2) * scale + height / 2;
                })
                .attr("r", function(d) {
                    const scale = width / (width + d.z);
                    return Math.max(0.1, d.r * scale);
                })
                .attr("opacity", function(d) {
                    return Math.min(1, Math.max(0.1, 1 - d.z / width));
                });
            
            requestAnimationFrame(animateStars);
        }

        animateStars();
    </script>
</body>
</html>
