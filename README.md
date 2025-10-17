# Sales Summary Dashboard

This project provides a simple, single-page web application to display a summary of sales data from a `data.csv` file.

## Features

- Fetches `data.csv` asynchronously.
- Calculates the total sum of the 'sales' column.
- Displays the total sales in a prominent section.
- Dynamically updates the page title with a sales summary and current date.
- Built with responsive design using Tailwind CSS.

## Setup and Usage

To run this application, ensure you have the `index.html` and `data.csv` files in the same directory.

1.  **Place `data.csv`**: Make sure your `data.csv` file is in the same folder as `index.html`.
2.  **Open `index.html`**: Simply open `index.html` in your web browser. The page will automatically fetch the `data.csv` file, process it, and display the total sales.

### `data.csv` Format

The `data.csv` file is expected to have a header row, and one of the columns must be named `sales` (case-insensitive) containing numeric values. For example:

```csv
id,product,sales,region
1,Laptop,1200,North
2,Mouse,25,South
3,Keyboard,75,East
4,Monitor,300,West
```

## Technologies Used

-   HTML5
-   JavaScript (ES6+)
-   Tailwind CSS (CDN)

## Contributing

Feel free to fork this repository and make improvements. For major changes, please open an issue first to discuss what you would like to change.
