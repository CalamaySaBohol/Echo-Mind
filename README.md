<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="min-h-screen flex flex-col items-center justify-center bg-gray-100">
    <!-- Navigation Bar -->
    <nav class="bg-white shadow-md py-4 px-6 flex justify-center items-center w-full">
        <div class="flex space-x-6">
            <a href="#" class="text-gray-700 font-semibold hover:text-blue-600">Anxiety Assessment</a>
            <a href="#" class="text-gray-700 font-semibold hover:text-blue-600">Anxiety Types/Levels</a>
            <a href="#" class="text-gray-700 font-semibold hover:text-blue-600">Resources</a>
            <a href="#" class="text-gray-700 font-semibold hover:text-blue-600">About Us</a>
        </div>
        <div class="flex space-x-6 ml-10">
            <a href="#" class="bg-blue-600 text-white px-6 py-2 rounded-lg hover:bg-blue-700">Login</a>
            <a href="#" class="bg-blue-600 text-white px-6 py-2 rounded-lg hover:bg-blue-700">Signup</a>
        </div>
    </nav>

    <!-- Main Content -->
    <div class="flex flex-col items-center justify-center min-h-screen p-4">
        <div class="max-w-2xl text-center bg-white p-6 rounded-2xl shadow-lg">
            <h1 class="text-3xl font-bold mb-4">Welcome to Our Anxiety Assessment Tool</h1>
            <p class="text-gray-600 mb-6">
                This tool helps you understand different anxiety types and levels while providing valuable resources.
            </p>
            <div class="flex justify-center">
                <button class="bg-blue-600 hover:bg-blue-700 text-white px-6 py-2 rounded-lg">
                    Start Assessment
                </button>
            </div>
        </div>
    </div>
</body>
</html>
