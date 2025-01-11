# KoinX Frontend Intern Assignment

This project is a frontend implementation of the KoinX assignment, created using **Vite** and **Tailwind CSS**. The task was to convert a Figma design into code using React.js (or Next.js), integrate APIs, and ensure responsiveness and usability.

## Features

- **Bitcoin Price Fetching**: Integrated with the [Coingecko API](https://www.coingecko.com/api/documentation) to fetch live Bitcoin prices in **USD** and **INR**, as well as the 24-hour change.
- **Trending Coins**: Fetched the top 3 trending coins using the Coingecko `/search/trending` API.
- **Responsive UI**: Developed a responsive design based on the provided Figma file, ensuring a seamless experience on various devices.
- **TradingView Chart Integration**: Embedded TradingView's advanced chart widget for Bitcoin (BTC/USD) in the chart component as per the Figma design.
- **You May Also Like Section**: Displayed the top trending coins with their logo, symbol, price, price change, and price graph in a horizontally scrollable carousel.

## Technologies Used

- **React.js** (via Vite)
- **Tailwind CSS** (for styling)
- **Coingecko API** (for fetching cryptocurrency data)
- **TradingView Widget** (for BTC/USD charts)
- **Vercel/Netlify** (for deployment)

## Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/koinx-frontend-assignment.git
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Run the development server:

    ```bash
    npm run dev
    ```

4. Open the project in your browser:

    ```bash
    http://localhost:3000
    ```

## APIs Used

1. **Coingecko /simple/price API**: Fetches the live price of Bitcoin in USD and INR, along with the 24-hour change.

2. **Coingecko /search/trending API**: Fetches the top 3 trending coins.

3. **TradingView Widget**: Embedded chart widget for Bitcoin prices (BTC/USD).

## Optional Features

- Dynamic token display based on the URL (e.g., `/bitcoin` or `/ethereum`).
- Fetching the coin symbol dynamically from the Coingecko `/coins/{id}` API to render the relevant price chart from TradingView.

## Deployment

The project has been deployed using **Vercel/Netlify**. You can view the live project here: [Insert your live project link].

## Notes

- The project follows best practices for code structure and clean code.
- Version control is utilized for managing commits and project changes.
- UI is fully responsive, ensuring proper display across devices.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
