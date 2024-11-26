<h1>Global Economic Development Trends - Power BI Analysis</h1>

  <h2>Overview</h2>
    <p>This repository provides a detailed analysis of global economic trends using a curated dataset and a Power BI report. The data spans the years 2015 to 2023 and covers key economic, social, and environmental indicators for various countries. This project aims to uncover insights into GDP, inflation, trade, energy consumption, labor markets, and human development, offering a comprehensive view of global development.</p>

  <h2>Features</h2>
    <ul>
        <li><strong>Dataset:</strong> A clean and structured dataset with seven interconnected tables:
            <ol>
                <li><strong>Country_Economic_Indicators:</strong> GDP, inflation rate, unemployment rate, population.</li>
                <li><strong>Sector_Development:</strong> Sectoral GDP contribution and employment.</li>
                <li><strong>Education_and_Healthcare:</strong> Literacy rate, health expenditure, life expectancy, school enrollment.</li>
                <li><strong>Trade_Development:</strong> Export, import, and trade balance.</li>
                <li><strong>Energy_Consumption:</strong> Energy consumption by source and CO2 emissions.</li>
                <li><strong>Labor_Market:</strong> Labor force, employment rate, and youth unemployment.</li>
                <li><strong>Innovation_Development:</strong> R&D spending, patent applications, and high-tech exports.</li>
            </ol>
        </li>
        <li><strong>Power BI Report:</strong>
            <ul>
                <li>Page 1: Global Economic Health Overview (GDP, population, unemployment).</li>
                <li>Page 2: Sector Development Analysis (sectoral contributions to GDP and employment).</li>
                <li>Page 3: Education and Healthcare Insights (literacy rate, life expectancy).</li>
                <li>Page 4: Trade and Energy Consumption Analysis (trade balance, energy sources, CO2 emissions).</li>
            </ul>
        </li>
        <li><strong>Interconnected Analysis:</strong> Establish relationships between tables via shared fields like <code>Country</code> and <code>Year</code>.</li>
    </ul>

  <h2>Key Visualizations</h2>
    <ol>
        <li><strong>GDP Trend Over Time:</strong> Line chart showing GDP growth for each country.</li>
        <li><strong>Sector-Wise Contribution:</strong> Tree map highlighting sectoral contributions to GDP.</li>
        <li><strong>Trade Balance Over Time:</strong> Area chart displaying surplus/deficit trends.</li>
        <li><strong>Energy Source Share:</strong> Donut chart visualizing energy consumption by type.</li>
        <li><strong>Health Expenditure vs. Life Expectancy:</strong> Clustered column and line chart.</li>
    </ol>

  <h2>Technologies Used</h2>
    <ul>
        <li><strong>Dataset:</strong> Prepared in Excel.</li>
        <li><strong>Visualization:</strong> Power BI Desktop.</li>
        <li><strong>Languages:</strong> DAX for custom measures and calculations.</li>
    </ul>

  <h2>Getting Started</h2>
    <ol>
        <li>Clone the repository:
            <pre><code>git clone https://github.com/your-username/global-economic-development-trends.git</code></pre>
        </li>
        <li>Open the dataset file (<code>Global_Economic_Development_Data.xlsx</code>) in Excel for review.</li>
        <li>Open the Power BI <code>.pbix</code> file in Power BI Desktop to explore the visuals and perform analysis.</li>
    </ol>

  <h2>Dataset Description</h2>
    <table border="1">
        <thead>
            <tr>
                <th>Table Name</th>
                <th>Key Columns</th>
                <th>Purpose</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Country_Economic_Indicators</td>
                <td>Country, Year, GDP, Inflation Rate</td>
                <td>Tracks core economic metrics.</td>
            </tr>
            <tr>
                <td>Sector_Development</td>
                <td>Country, Year, Sector, Employment</td>
                <td>Shows sector contributions to GDP and employment.</td>
            </tr>
            <tr>
                <td>Education_and_Healthcare</td>
                <td>Literacy Rate, Health Expenditure</td>
                <td>Focuses on social development indicators.</td>
            </tr>
            <tr>
                <td>Trade_Development</td>
                <td>Export, Import, Trade Balance</td>
                <td>Captures trade data and performance.</td>
            </tr>
            <tr>
                <td>Energy_Consumption</td>
                <td>Energy Source, CO2 Emissions</td>
                <td>Tracks energy usage and emissions.</td>
            </tr>
            <tr>
                <td>Labor_Market</td>
                <td>Employment Rate, Youth Unemployment</td>
                <td>Analyzes labor market trends.</td>
            </tr>
            <tr>
                <td>Innovation_Development</td>
                <td>R&D, Patent Applications</td>
                <td>Measures technological growth and innovation.</td>
            </tr>
        </tbody>
    </table>

  <h2>Insights and Analysis</h2>
    <ul>
        <li><strong>Economic Growth:</strong> Trends in GDP, inflation, and unemployment across regions.</li>
        <li><strong>Sector Analysis:</strong> Identification of dominant sectors and their impact on economies.</li>
        <li><strong>Social Development:</strong> Correlation between healthcare, education, and economic growth.</li>
        <li><strong>Sustainability:</strong> Energy consumption patterns and CO2 emissions by source.</li>
    </ul>

  <h2>Contributing</h2>
    <p>Feel free to open issues or create pull requests if you would like to contribute to the dataset or improve the Power BI report.</p>

  <h2>License</h2>
    <p>This project is licensed under the MIT License.</p>
