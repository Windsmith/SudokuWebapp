```<!DOCTYPE HTML5>
{% load static %}

<html>
    <head>
        <title>Sudoku Web</title>
        <link href="/static/mainapp/tailwind-output.css" rel="stylesheet" type="text/css">
        <link rel="shortcut icon" href="{% static 'images/favicon.ico' %}" />
    </head>
    <body class="transform h-32 bg-gradient-to-b from-teal-300 to-blue-700 justify-center">
        
        <div class="transform m-auto pt-24 lg:pt-32 animate-fall overflow-hidden">
            <h2 class="transform mainfont text-center text-4xl sm:text-5xl md:text-6xl xl:text-8xl text-white bold overflow-hidden animate-pulse"> SUDOKU </h2>
        </div>

        <div class="flex flex-col items-center pt-10">

            <a href="game" class="transform bg-gray-300 active:bg-gray-500 pl-4 pb-1 pr-4 rounded hover:scale-105 shadow-xl opacity-75 hover:opacity-100 transition-all duration-200 ease-in-out subfont-cumono text-sm sm:text-xl md:text-2xl lg:text-3xl xl:text-4xl">START GAME</a>
            <a href="leaderboard/lb" class="transform bg-gray-300 active:bg-gray-500 pl-4 pr-4 pt-1 pb-1 mt-6 rounded hover:scale-105 shadow-xl opacity-75 hover:opacity-100 transition-all duration-150 ease-in-out subfont-cumono text-sm sm:text-xl md:text-2xl lg:text-3xl xl:text-4xl">LEADERBOARD</a>

        </div>
    </body>
</html>
```