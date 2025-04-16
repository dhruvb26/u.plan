# u-plan

u-plan is a web platform designed for construction planners, governments, and urban developers to gather crucial environmental insights by simply entering a zipcode. The platform helps users make data-driven decisions for sustainable urban development, focusing on reducing the Urban Heat Island (UHI) effect, increasing vegetation cover, and selecting materials with better albedo for energy efficiency.

## Features

- **UHI Index**: Provides the temperature difference between urban and rural areas.
- **Vegetation Cover**: Displays the percentage of vegetation in the area, helping in the planning of green spaces.
- **Albedo**: Shows the reflectivity of surfaces, enabling the selection of materials to reduce heat absorption.
- **Climate Risks**: Highlights potential climate risks such as heatwaves or flood risks in the area.
- **Built Environment Data**: Displays the number of homes at risk and other crucial infrastructure information.

## How It Works

1. **Enter a Zipcode**: Get instant data on Urban Heat Island index, vegetation cover, albedo, and climate risks for the selected area.
2. **Analyze the Data**: Use the provided insights to plan urban projects, such as building energy-efficient structures or increasing green spaces.
3. **Actionable Insights**: Get customized recommendations for sustainable planning, improving public health, and reducing the environmental impact.

## Installation

### Prerequisites

Make sure you have the following installed:

- **Node.js** (version 16 or higher)
- **Python** (version 3.11 or higher)
- **Google Earth Engine API** (for environmental data)
- **Mapbox API** (for interactive maps)
- **Conda** (for managing Python environments)

### Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/u-plan.git
   ```
2. **Navigate to the Project Directory**:

   ```bash
   cd u-plan
   ```

3. **Install Dependencies**:

   - For the **frontend**:
     ```bash
     npm install
     ```
   - For the **backend**:
     Make sure you're in the root folder and install backend dependencies via pip or Conda:
     ```bash
     pip install -r requirements.txt
     ```

4. **Set Up Environment Variables**:

   - Create a `.env` file in the root directory and add the following environment variables:
     ```bash
     MAPBOX_API_KEY=your-mapbox-api-key
     GOOGLE_EARTH_ENGINE_CREDENTIALS=your-gee-credentials
     ```

5. **Run the Application**:

   - Start the frontend server:
     ```bash
     npm run dev
     ```
   - Start the backend server:
     ```bash
     python app.py
     ```

6. **Access the Application**:
   Visit `http://localhost:3000` in your browser to start using u-plan.

## Technologies Used

- **Next.js**: Frontend framework for server-side rendering.
- **Python**: Backend logic and data processing.
- **Google Earth Engine API**: For gathering environmental data such as UHI, vegetation cover, and albedo.
- **Mapbox**: For interactive mapping and visualizing zipcode data.
- **Conda**: For managing Python environments.
- **SQLite**: For local database management.

## Contribution Guidelines

We welcome contributions to improve u-plan! Here’s how you can help:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a Pull Request.

For major changes, please open an issue to discuss your proposed changes beforehand.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

This README provides a comprehensive overview of the u-plan project, setup instructions, and contribution guidelines, which are essential for any open-source or collaborative project on GitHub.
