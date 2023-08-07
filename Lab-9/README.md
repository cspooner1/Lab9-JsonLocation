# Lab 9 - JSON Data Analysis with LINQ

## 1. What is this code?
This C# code is a data analysis application that reads and deserializes JSON data from a file. It uses the System.Text.Json library to handle JSON data. The program performs various LINQ queries to analyze and manipulate the JSON data related to neighborhood locations. The goal is to extract meaningful information from the JSON data and present it in a structured manner.

## 2. Visuals - How it looks in action
Read file into string
Deserialized the json data
Lab_9.Geometry+Location[]

Part 1 - All Neighborhoods Grouped

Chelsea: 7
Lower East Side: 1
Gramercy Park: 3
Financial District: 30
Civic Center: 2
Tribeca: 1
: 4
East Village: 2
Greenwich Village, SoHo: 1
SoHo, Tribeca: 1
Greenwich Village: 1
Kips Bay, Murray Hill: 1
Midtown East: 3
Garment District: 7
Midtown West: 1
Diamond District, Midtown: 1
Upper East Side: 4
Upper West Side: 6
Manhattan Valley: 1
Harlem: 3
Morningside Heights, Harlem: 1
Spanish Harlem: 1
Sugar Hill, Upper Manhattan: 1
Washington Heights: 1
Hudson Heights: 2
Inwood: 1
East Harlem: 1
Hell's Kitchen: 2
Upper Manhattan: 1
Roosevelt Island: 1
Midtown: 37
Hunter College, Rockefeller University: 1
Battery Park City: 6
Manhattanville: 1
Murray Hill: 4
Carnegie Hill: 1
Yorkville: 1
Lenox Hill: 1
Kips Bay: 2
South Cove: 1

Part 2 - All Neighboorhoods with Names

Chelsea
Lower East Side
Gramercy Park
Financial District
Civic Center
Financial District
Tribeca
East Village
Gramercy Park
Chelsea
Greenwich Village, SoHo
SoHo, Tribeca
Greenwich Village
Kips Bay, Murray Hill
Midtown East
Garment District
Midtown West
Diamond District, Midtown
Upper East Side
Midtown East
Upper West Side
Upper West Side
Manhattan Valley
Harlem
Morningside Heights, Harlem
Upper East Side
Spanish Harlem
Harlem
Sugar Hill, Upper Manhattan
Washington Heights
Hudson Heights
Inwood
East Harlem
Hell's Kitchen
Harlem
Civic Center
Upper Manhattan
Hudson Heights
Financial District
Financial District
Roosevelt Island
Financial District
Midtown
Midtown
Hunter College, Rockefeller University
Upper West Side
Upper East Side
Battery Park City
Financial District
Midtown
Financial District
Midtown
Midtown
Midtown
Midtown
Midtown
Midtown
Hell's Kitchen
Midtown
Midtown
Midtown
Chelsea
Manhattanville
Chelsea
Chelsea
Murray Hill
Garment District
Garment District
Garment District
Garment District
Garment District
Midtown
Upper West Side
Midtown
Carnegie Hill
Midtown
Yorkville
Lenox Hill
Upper West Side
Upper West Side
Chelsea
Midtown
Midtown
Midtown
Midtown
Midtown
Midtown
Midtown
Chelsea
Murray Hill
Kips Bay
Kips Bay
Financial District
Upper East Side
Midtown
Midtown
Midtown
Midtown
Midtown
Midtown
Midtown
Midtown
Midtown
Midtown
Midtown
Murray Hill
Midtown
Midtown
Midtown East
Murray Hill
Midtown
Midtown
Garment District
Financial District
East Village
Financial District
Financial District
Financial District
Financial District
Financial District
Financial District
Financial District
Financial District
Financial District
Financial District
Financial District
Financial District
Financial District
Financial District
Financial District
Financial District
Financial District
Financial District
Gramercy Park
Financial District
Financial District
Financial District
South Cove
Battery Park City
Battery Park City
Battery Park City
Battery Park City
Battery Park City

Part 3 - All Neighboorhood Names - No Duplicates

Chelsea
Lower East Side
Gramercy Park
Financial District
Civic Center
Tribeca
East Village
Greenwich Village, SoHo
SoHo, Tribeca
Greenwich Village
Kips Bay, Murray Hill
Midtown East
Garment District
Midtown West
Diamond District, Midtown
Upper East Side
Upper West Side
Manhattan Valley
Harlem
Morningside Heights, Harlem
Spanish Harlem
Sugar Hill, Upper Manhattan
Washington Heights
Hudson Heights
Inwood
East Harlem
Hell's Kitchen
Upper Manhattan
Roosevelt Island
Midtown
Hunter College, Rockefeller University
Battery Park City
Manhattanville
Murray Hill
Carnegie Hill
Yorkville
Lenox Hill
Kips Bay
South Cove

Part 4 - ComboQuery

Chelsea
Lower East Side
Gramercy Park
Financial District
Civic Center
Tribeca
East Village
Greenwich Village, SoHo
SoHo, Tribeca
Greenwich Village
Kips Bay, Murray Hill
Midtown East
Garment District
Midtown West
Diamond District, Midtown
Upper East Side
Upper West Side
Manhattan Valley
Harlem
Morningside Heights, Harlem
Spanish Harlem
Sugar Hill, Upper Manhattan
Washington Heights
Hudson Heights
Inwood
East Harlem
Hell's Kitchen
Upper Manhattan
Roosevelt Island
Midtown
Hunter College, Rockefeller University
Battery Park City
Manhattanville
Murray Hill
Carnegie Hill
Yorkville
Lenox Hill
Kips Bay
South Cove
Lower East Side

## 3. How to use the Lab 9 Application - Step by step directions (Happy Path Walkthrough)
1. **Run the program:** Execute the application in a C# environment or IDE. The console will display the message "Read file into string" and "Deserialized the json data" after reading and processing the JSON data.

2. **Part 1 - All Neighborhoods Grouped:**
   - Uncomment the code block in the `Part1WithLINQ` method or `Part1` method (remove the `//` comments).
   - Run the application.
   - The program will group the neighborhood locations and display each neighborhood along with the count of appearances in the JSON data.

3. **Part 2 - All Neighborhoods with Names:**
   - Uncomment the code block in the `Part2` method.
   - Run the application.
   - The program will display all neighborhood names with coordinates.

4. **Part 3 - All Neighborhood Names - No Duplicates:**
   - Uncomment the code block in the `Part3` method.
   - Run the application.
   - The program will display all neighborhood names without duplicates.

5. **Part 4 - ComboQuery:**
   - Uncomment the code block in the `Part4` method.
   - Run the application.
   - The program will combine queries from Part 2 and Part 3 to display distinct neighborhood names.

6. **Part 5 - Rewriting Queries with Different Methods:**
   - Uncomment the code block in the `Part5` method.
   - Run the application.
   - The program will rewrite Part 1 and Part 2 queries using different LINQ methods.

## 4. Other Relevant Details
- The application reads JSON data from the file specified in the `File.ReadAllText` method. Make sure to update the file path if needed.
- The program uses LINQ queries to manipulate JSON data, providing a concise and efficient way to analyze the information.
- This Lab 9 Application is designed for educational purposes, focusing on LINQ and JSON data handling. It lacks user interaction and real-world features present in fully-fledged applications.