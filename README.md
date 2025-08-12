# star-catalog-generator
The application streamlines the process by automatically detecting and measuring stars within an uploaded astronomical image.
Star Catalog Generator is a novel web-based application designed to assist amateur astronomers in the tedious and time-consuming task of manually creating star catalogs from digital images. Run it in your updated browser. All you need to do is download the HTML file.

### How to Use the Star Catalog Generator

1.  **Load an Image:**
    
    *   Click the "Select Image" button.
        
    *   Choose a digital astronomical image from your computer (e.g., a .jpg, .png, or .tif file). The image will load and display in the main canvas area.
        
2.  **Adjust the Threshold:**
    
    *   Find the "Star Detection Threshold" slider in the control panel.
        
    *   Drag the slider to the right to increase the threshold, which will make the app detect only brighter stars. Drag it to the left to decrease the threshold and detect fainter stars.
        
    *   Watch the canvas and the "Stars Detected" counter in the status bar to find the optimal threshold that best separates the stars from the background noise.
        
3.  **Use the Advanced Settings:**
    
    *   Click the "Advanced Settings" button to expand the options.
        
    *   **Blur Radius:** Adjust the "Blur Radius" slider to smooth the image and reduce noise. A larger radius can help with grainy images but may blur smaller stars.
        
    *   **Minimum Star Area:** Use the "Minimum Star Area" slider to filter out noise or cosmic ray artifacts. Stars with an area below this value will be ignored.
        
    *   **Background Subtraction:** Check the "Enable Background Subtraction" box if your image has a non-uniform or bright background.
        
    *   **FWHM Calculation:** Check the "Enable FWHM Calculation" box to have the application calculate the Full Width at Half Maximum for each star. This is a measure of star sharpness.
        
4.  **Explore the Results:**
    
    *   **View Buttons:** Use the view buttons at the bottom of the canvas to switch between different displays:
        
        *   **Original:** Shows the raw, uploaded image.
            
        *   **Threshold:** Displays the binary image after thresholding, showing you exactly what the algorithm is detecting.
            
        *   **Stars:** Overlays a star map on the original image, marking each detected star with a circle and its ID number.
            
    *   **Star Table:** Click the "Show Star Catalog" button to display a table of all the detected stars and their properties.
        
    *   **Sort Data:** Click on the table headers (e.g., "ID", "X", "Y", "Flux", "Area", "Magnitude", "FWHM") to sort the star list.
        
    *   **Hover for Details:** When in the "Stars" view, hover your mouse over a detected star to see a tooltip with its detailed properties.
        
5.  **Export the Data:**
    
    *   Click the "Export Catalog" button.
        
    *   A modal window will appear, allowing you to select which fields you want to include in your output file.
        
    *   Choose your desired file format (CSV or JSON).
        
    *   Click "Download" to save the star catalog to your computer.
