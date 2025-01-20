# Amazon Smbhav 2024 - Sustainable Packaging Recommender  

## Instructions  

### Deployment Link  
**Access the deployed model here**: **[Live Demo](https://sustainable-packaging-recommender.onrender.com/)**  
Note: The initial load of the model might take some time due to server processing. If the model does not load after a few minutes, kindly check the status of the deployment or try again later.

### Input Details  
To use the recommender system, the user needs to provide:  
1. **Location** – The region where packaging is required
2. **Product Type** – the type of product to be packaged

**Note**: Both inputs (Location and Product Type) should start with a capital letter. You can choose one of the examples provided below for both fields:  
1. **Example Locations**: "Bangalore", "Mumbai", "Delhi", "Jaipur", "Chennai", etc  
2. **Example Product Types**: "Electronics", "Beauty Products", "Food", "Apparel", "Books", etc

### Expected Output  
The system will provide:  
- **Recommended Packaging Material** best suited for the product and location.  
- **Sustainability Score** detailing eco-friendliness of the material.  
- **Alternative Locations** if the preferred packaging material is unavailable in the requested location.  
---  
## Overview  
The Sustainable Packaging Recommender is a machine learning model developed for Amazon Smbhav 2024, designed to suggest eco-friendly packaging materials based on product type and location. The model helps businesses choose sustainable packaging solutions by analyzing factors such as recyclability, biodegradability, and carbon footprint. If a recommended packaging material is not available in the specified location, the model suggests the nearest available location, ensuring efficient sourcing while promoting sustainability.

---  
## Dataset  
The model is trained on a comprehensive dataset that includes:  
- **Product Categories**: Electronics, clothing, perishables, etc.  
- **Packaging Materials**: Recycled cardboard, biodegradable plastics, compostable alternatives.  
- **Location Data**: Availability of materials across different regions.  
- **Sustainability Factors**: Carbon footprint, decomposition rate, and recyclability scores.
---
