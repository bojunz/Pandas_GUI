# Pandas_GUI
![Shanshui GIF](https://github.com/bojunz/Pandas_GUI/raw/main/shanshui.gif)


# Abstract
This project is designed to assist non-technical users in decision-making through data analysis by providing intuitive visualizations such as time series diagrams, bar charts, data summaries, and automatic text summaries. Developed in Python, the project utilizes key libraries including pandas, tkinter, canvas, matplotlib, multiprocessing, and pickle. The process begins with analyzing the dataset according to specific requirements or significant patterns, followed by the generation of relevant charts. These visualizations are then integrated into a desktop graphical user interface (GUI). The final product enables users to access and interact with various charts through a single click, allowing for easy navigation and detailed examination of the data. Additionally, users can generate summaries of the chart content with a single click, enhancing their ability to make informed decisions.
## Key process
| Iteration | Description                                                                                 |
|-----------|---------------------------------------------------------------------------------------------|
| 1         | Define the main functionality framework with three windows: login window, main interface, and display window. |
| 2         | Enhance UI design by adjusting the layout of the login window, adding CAPTCHA functionality, and including a GIF. |
| 3         | Adjust the UI of the main page, add visual enhancements with GIFs, and address a bug where prolonged GIF loading causes freezes between the login window and the main page. |
| 4, 5, 6   | Resolve freeze issues using multi-threading and further enhance UI aesthetics.               |
| 7         | Refine visualization charts to ensure all functionalities are working correctly.              |
| 8         | Add registration functionality, store user credentials using pickle, and implement registration and login verification. |
| 9         | Implement a feature to display logged-in user information on the main page.                  |
| 10        | Introduce a dataset selection window to allow users to choose, drag, and input datasets for analysis. |
| 11        | Add language switch functionality to toggle between English and Chinese on the main and display pages. |
| 12        | Implement a one-click summary feature for charts to generate textual summaries of different chart types. |
# Demo
## Login window

<table>
<tr>
<td>
<img src="https://github.com/bojunz/Pandas_GUI/raw/main/Demo_Login_page.gif" alt="Demo Login Page GIF" style="border: 2px solid black; max-width: 100%; height: auto;">
</td>
<td>

### Features

- Verification code function
- Login verification function
- Register function

</td>
</tr>
</table>


## Home window
<table>
<tr>
<td>
<img src="https://github.com/bojunz/Pandas_GUI/blob/main/Demo_Home_Page.gif" alt="Demo Login Page GIF" style="border: 2px solid black; max-width: 100%; height: auto;">
</td>
<td>

### Features

- File Upload Capability
- User Authentication and Login Management
- User Access Authorization
- Customizable Graph Selection

</td>
</tr>
</table>

### File selection window
- File Browsing Interface: Provides an intuitive interface for navigating directories and selecting files from the system.
- Drag and Drop Support: Enables users to drag files from their file explorer directly into the selection window for quick and easy file uploads.
- Progress Bar: Displays a progress bar during file selection and upload processes to inform users of the current status and estimated time remaining.
- Single and Directory Selection: Supports the selection of both individual files and entire directories, offering flexibility based on user needs.

- ## Display window
<table>
<tr>
<td>
<img src="https://github.com/bojunz/Pandas_GUI/blob/main/Demo_Display_Page.png" alt="Demo Login Page GIF" style="border: 2px solid black; max-width: 100%; height: auto;">
</td>
<td>

### Features

- Multiple Graph Types: Offers various graph formats for visualization
- Customizable: Lets users select and customize different data items
- Clear Comparisons: Easily compares differences between data points
- Interactive Exploration: Allows interaction with data
- Data Highlighting: Emphasizes key data points and trends.
- Export Options: Provides export and sharing capabilities for graphs.
</td>
</tr>
</table>
