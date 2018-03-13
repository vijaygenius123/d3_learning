# Making Creating A Circle  More Readable

1. Selecting the body element
    ```html
        var bodySelection = d3.select("body");
    ```
    This selects the body element and assigns it to bodySelection variable

2. Appending svg to the bodyElement
    ```html
       var svgSelection = bodySelection.append("svg")
                                        .attr("height",50)
                                        .attr("width",50);
    ```
    This appends an svg element with hright and with of 50 to the body and assigns it to the svgSelection variable

3. Create a circle inside the svg element
    ```html
        var circleSelection = svgSelection.append("circle")
                                            .attr("cx",25)
                                            .attr("cy",25)
                                            .attr("r",25)
                                            .attr("fill",purple")
    ```
    This will create a circle of radius 25 at (25,25) inside the svg and assign it to circleSelection variable
