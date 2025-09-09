<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Caz Rooney Analytics Portfolio</title>
    <!-- Use the Inter font from Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f3f4f6;
            color: #1f2937;
        }
    </style>
</head>
<body class="antialiased leading-relaxed text-gray-800">

    <div class="min-h-screen flex flex-col items-center py-10 px-4 sm:px-6 lg:px-8">
        <!-- Header -->
        <header class="w-full max-w-4xl text-center mb-12">
            <h1 class="text-4xl sm:text-5xl font-extrabold text-gray-900 mb-2">Caz Rooney Analytics Portfolio</h1>
            <p class="text-lg text-gray-600">A showcase of data projects and machine learning applications.</p>
        </header>

        <!-- Main Content - Project Grid -->
        <main class="w-full max-w-5xl">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">

                <!-- Project Card 1: Bike Share Analysis -->
                <div class="bg-white rounded-xl shadow-lg p-6 flex flex-col justify-between transform transition duration-300 hover:scale-105 hover:shadow-2xl">
                    <div>
                        <h2 class="text-2xl font-bold text-gray-900 mb-2">Bike Share Analysis</h2>
                        <p class="text-gray-600 mb-4">
                            A comprehensive analysis of bike share data to identify usage patterns, peak hours, and popular routes. The project includes data cleaning, exploratory data analysis, and a visualization dashboard.
                        </p>
                    </div>
                    <div class="flex flex-col sm:flex-row space-y-3 sm:space-y-0 sm:space-x-3 mt-4">
                        <a href="https://dpriestley09.github.io/London_Bike_Analysis/" target="_blank" class="w-full sm:w-auto text-center bg-blue-600 text-white font-medium py-2 px-4 rounded-lg shadow-md transition duration-300 hover:bg-blue-700">
                            View Dashboard
                        </a>
                        <a href="https://github.com/dpriestley09/London_Bike_Analysis" target="_blank" class="w-full sm:w-auto text-center bg-gray-200 text-gray-800 font-medium py-2 px-4 rounded-lg shadow-md transition duration-300 hover:bg-gray-300">
                            View Repository
                        </a>
                    </div>
                </div>

                <!-- Project Card 2: Titanic Survival Prediction -->
                <div class="bg-white rounded-xl shadow-lg p-6 flex flex-col justify-between transform transition duration-300 hover:scale-105 hover:shadow-2xl">
                    <div>
                        <h2 class="text-2xl font-bold text-gray-900 mb-2">Titanic Survival Prediction</h2>
                        <p class="text-gray-600 mb-4">
                            A machine learning project using a logistic regression model to predict the survival of passengers on the Titanic. The project focuses on data preprocessing, feature engineering, and model evaluation.
                        </p>
                    </div>
                    <div class="flex flex-col sm:flex-row space-y-3 sm:space-y-0 sm:space-x-3 mt-4">
                        <a href="https://github.com/dpriestley09/Titanic_Survivor_Analysis" target="_blank" class="w-full sm:w-auto text-center bg-blue-600 text-white font-medium py-2 px-4 rounded-lg shadow-md transition duration-300 hover:bg-blue-700">
                            View Notebook
                        </a>
                        <a href="https://github.com/dpriestley09/Titanic_Survivor_Analysis" target="_blank" class="w-full sm:w-auto text-center bg-gray-200 text-gray-800 font-medium py-2 px-4 rounded-lg shadow-md transition duration-300 hover:bg-gray-300">
                            View Repository
                        </a>
                    </div>
                </div>

                <!-- Project Card 3: Wine Quality Analysis -->
                <div class="bg-white rounded-xl shadow-lg p-6 flex flex-col justify-between transform transition duration-300 hover:scale-105 hover:shadow-2xl">
                    <div>
                        <h2 class="text-2xl font-bold text-gray-900 mb-2">Wine Quality Analysis</h2>
                        <p class="text-gray-600 mb-4">
                            An analytical project to determine the factors that contribute to wine quality. This project uses correlation analysis and data visualization to explore the relationship between chemical properties and quality ratings.
                        </p>
                    </div>
                    <div class="flex flex-col sm:flex-row space-y-3 sm:space-y-0 sm:space-x-3 mt-4">
                        <a href="https://dpriestley09.github.io/Wine_Analysis_Dashboard/" target="_blank" class="w-full sm:w-auto text-center bg-blue-600 text-white font-medium py-2 px-4 rounded-lg shadow-md transition duration-300 hover:bg-blue-700">
                            View Dashboard
                        </a>
                        <a href="https://github.com/dpriestley09/Wine_Analysis_Dashboard" target="_blank" class="w-full sm:w-auto text-center bg-gray-200 text-gray-800 font-medium py-2 px-4 rounded-lg shadow-md transition duration-300 hover:bg-gray-300">
                            View Repository
                        </a>
                    </div>
                </div>

            </div>
        </main>

        <!-- Footer -->
        <footer class="w-full max-w-4xl text-center mt-12 py-6 border-t border-gray-200 text-gray-500 text-sm">
            <p>&copy; 2024 Caz Rooney Analytics. All rights reserved.</p>
        </footer>
    </div>
</body>
</html>
