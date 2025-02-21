
# Historic Villages - Web Project

## Description
This project is a client-side web application that provides information about a set of historic villages in Portugal. The website has multiple pages that offer details about each village, including images, videos, weather forecast, and more. 

## Pages Structure

### 1. **Home Page**
The main page is structured into four sections:
- **Header**: Contains the project title and logo.
- **Navigation (nav)**: Includes links for navigating within the website.
- **Main**: Features a slideshow (using Bootstrap or jQuery) displaying images of five villages. Each image links to the corresponding village page. Additionally, it integrates a promotional video for the historic villages ([YouTube Video](https://www.youtube.com/watch?v=kP2OtQrVm1o&t)).
- **Footer**: Displays the author's name.

### 2. **Village Pages**
Each village page contains the following:
- **Header and Navigation**: Inherited from the home page.
- **Text Information**: Descriptive content about the village.
- **Image Slideshow**: A Bootstrap or jQuery slideshow with pictures of the village.
- **Google Maps**: A map showing the location of the village.
- **Weather Forecast**: Weather information from the [IPMA API](https://api.ipma.pt/) for the village's location.
- **Videos**: One or more promotional videos about the village.
- **Additional Information**: For example, recommendations on what to visit or where to eat.

### 3. **Registration Page**
This page allows users to register with the following fields:
- **Name**: Required.
- **Email**: Required and must be validated for proper format.
- **Username**: Required, minimum 6 characters and maximum 20.
- **Password**: Required, minimum 6 characters and maximum 15.

The **Login** option is available on the home page and the village pages, displayed in a modal (using Bootstrap). The modal contains:
- Fields to input the username and password.
- Buttons to either hide the modal or confirm the login.

## Mandatory Features
- **HTML5**: Structure each page using HTML5 elements such as `header`, `nav`, `section`, `article`, `footer`.
- **CSS**: Styling defined in separate CSS files.
- **Navigation Bar**: Should follow the provided example.
- **Slideshow**: Implement a Bootstrap or jQuery slideshow on the main page and village pages.
- **Modal Login**: Include a modal for user login.
- **Videos and Maps**: Embed videos and maps on village pages.
  
## Data Sources
All the content (text and images) used in this project has been sourced from the following websites:
- [Aldeias Históricas de Portugal](https://aldeiashistoricasdeportugal.com/)
- [Visit Portugal](https://www.visitportugal.com/pt-pt/node/73751)
- [Turismo do Centro](https://turismodocentro.pt/artigo/as-12-aldeias-historicas-mesmo-aqui-a-beira/)
- [Turismo de Portugal](http://www.turismodeportugal.pt/pt/Paginas/homepage.aspx)
