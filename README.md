# Creating A Circle

1. Create a svg element 
    ```html
        d3.select("body")
            .append("svg")
            .attr("height",50)
            .attr("width",50);
    ```
    This creates an svg element inside body with height and width of 50px.

2. Create a circle inside the svg
    ```html
        d3.select("svg")
            .append("circle")
            .attr("cx",25)
            .attr("cy",25)
            .attr("r",25)
            .attr("fill",purple")
    ```
    This will create a circle of radius 25 at (25,25) inside the svg
