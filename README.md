# Event Management Website

This is a static website for event management deployed using Azure services.

## Overview

This website provides information about events and allows users to register for upcoming events.

## Azure Services Used

1. **Azure Static Web App:**
   The website is hosted and served using Azure Static Web App.

2. **Azure Storage Account:**
   CSS, JS, and images are stored in Azure Storage Containers for efficient content delivery.

3. **Azure CDN (Content Delivery Network):**
   Azure CDN service is used to deliver content, ensuring high availability and performance.

## Azure Resources Screenshots

### Azure Static Web App
![Azure Static Web App Screenshot](https://evento-ccerfqaegthphscc.z01.azurefd.net/images/static.png);

### Azure Storage Account

- **Azure Storage Account Overview:**
  Screenshot of the Azure Storage Account.

  ![Azure Storage Account Screenshot](https://evento-ccerfqaegthphscc.z01.azurefd.net/images/storage.png)

- **Azure Storage Containers:**
  Screenshot of Azure Storage Containers used for storing CSS, JS, and images.

  ![Azure Storage Containers Screenshot](https://evento-ccerfqaegthphscc.z01.azurefd.net/images/containers.png)

### Azure CDN
![Azure CDN Screenshot](https://evento-ccerfqaegthphscc.z01.azurefd.net/images/cdn.png)

### Azure Resource Group
![Azure Resource Group Screenshot](https://evento-ccerfqaegthphscc.z01.azurefd.net/images/reasource.png)

## Project Structure

- `/index.html`: The main HTML file for the website.
- `/css/`: Contains CSS stylesheets stored in Azure Storage.
- `/js/`: Contains JavaScript files stored in Azure Storage.
- `/images/`: Includes images used in the website stored in Azure Storage.

## How to Run Locally

To run the website locally, you'll need a web server. You can use a tool like [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) in Visual Studio Code.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/your-repository.git
