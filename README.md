\# 📊 Guvi Capstone Project --- PhonePe Pulse Data Visualization and Exploration



\## 🧩 Project Overview



This project aims to \*\*extract, transform, store, and visualize data\*\*

from the \*\*PhonePe Pulse GitHub repository\*\* to uncover insights about

digital payments across India.



Using \*\*Python, PostgreSQL, Streamlit, and Plotly\*\*, the project builds

an interactive dashboard that displays transaction trends, user growth,

and regional analytics.



------------------------------------------------------------------------



\## 🎯 Objectives



1\.  \*\*Data Extraction:\*\*

&nbsp;   -   Clone and collect data from the official \[PhonePe Pulse GitHub

&nbsp;       Repository](https://github.com/PhonePe/pulse).

2\.  \*\*Data Transformation:\*\*

&nbsp;   -   Clean, structure, and organize the raw JSON files into tabular

&nbsp;       formats using \*\*Python\*\* and \*\*Pandas\*\*.

3\.  \*\*Database Insertion:\*\*

&nbsp;   -   Create relational tables in \*\*PostgreSQL\*\*.\\

&nbsp;   -   Insert the transformed data for efficient querying.

4\.  \*\*Dashboard Creation:\*\*

&nbsp;   -   Build an interactive web-based \*\*Streamlit\*\* dashboard.\\

&nbsp;   -   Use \*\*Plotly\*\* for rich visualizations like bar charts,

&nbsp;       choropleth maps, and pie charts.

5\.  \*\*Data Retrieval \& Visualization:\*\*

&nbsp;   -   Dynamically fetch and visualize data directly from the

&nbsp;       PostgreSQL database.



------------------------------------------------------------------------



\## 🏗️ Tech Stack



&nbsp; -----------------------------------------------------------------------

&nbsp; Component                      Technology Used

&nbsp; ------------------------------ ----------------------------------------

&nbsp; \*\*Programming Language\*\*       Python



&nbsp; \*\*Data Extraction\*\*            Git, JSON



&nbsp; \*\*Data Processing\*\*            Pandas



&nbsp; \*\*Database\*\*                   PostgreSQL



&nbsp; \*\*Dashboard Framework\*\*        Streamlit



&nbsp; \*\*Visualization Library\*\*      Plotly Express \& Graph Objects



&nbsp; \*\*Additional Tools\*\*           Psycopg2, Requests, PIL, Streamlit

&nbsp;                                Option Menu

&nbsp; -----------------------------------------------------------------------



------------------------------------------------------------------------



\## ⚙️ Project Workflow



1\.  \*\*Data Extraction:\*\*

&nbsp;   -   Clone the PhonePe Pulse dataset from GitHub using:



&nbsp;       ``` bash

&nbsp;       git clone https://github.com/PhonePe/pulse.git

&nbsp;       ```



&nbsp;   -   Extract required JSON files (aggregated, map, and top data).

2\.  \*\*Data Transformation:\*\*

&nbsp;   -   Parse JSON data with Python scripts.\\

&nbsp;   -   Convert them into Pandas DataFrames.\\

&nbsp;   -   Clean and structure the data into tabular format.

3\.  \*\*Database Setup:\*\*

&nbsp;   -   Create a PostgreSQL database named `phonepay`.\\

&nbsp;   -   Define tables for:

&nbsp;       -   `aggregated\_transaction`

&nbsp;       -   `aggregated\_user`

&nbsp;       -   `aggregated\_insurance`

&nbsp;       -   `map\_transaction`

&nbsp;       -   `map\_user`

&nbsp;       -   `map\_insurance`

&nbsp;       -   `top\_transaction`

&nbsp;       -   `top\_user`

&nbsp;       -   `top\_insurance`

&nbsp;   -   Insert cleaned data into these tables using \*\*psycopg2\*\*.

4\.  \*\*Dashboard Development:\*\*

&nbsp;   -   Build a \*\*Streamlit\*\* app that connects to the PostgreSQL

&nbsp;       database.\\

&nbsp;   -   Integrate \*\*Plotly\*\* for visual charts and choropleth maps.\\

&nbsp;   -   Provide three main sections:

&nbsp;       -   \*\*Home\*\*

&nbsp;       -   \*\*Data Exploration\*\*

&nbsp;       -   \*\*Top Charts\*\*

5\.  \*\*Visualization:\*\*

&nbsp;   -   Explore transactions, users, and insurance data by \*\*year\*\*,

&nbsp;       \*\*quarter\*\*, and \*\*state\*\*.\\

&nbsp;   -   Visualize metrics such as:

&nbsp;       -   Total Transaction Amount\\

&nbsp;       -   Transaction Count\\

&nbsp;       -   User Growth\\

&nbsp;       -   Top Performing States/Districts



------------------------------------------------------------------------



\## 📈 Dashboard Features



\-   Interactive analysis by \*\*Year\*\*, \*\*Quarter\*\*, and \*\*State\*\*

\-   Aggregated, Map-based, and Top-level visual insights

\-   Real-time data fetch from PostgreSQL

\-   Choropleth maps of India showing state-level performance

\-   Comparative insights between different transaction types

\-   Mobile brand-wise user statistics



------------------------------------------------------------------------



\## 🧰 Installation Guide



\### 1. Clone the Repository



``` bash

git clone https://github.com/<your-username>/Guvi\_CAPSTON\_Project\_Phonepe-Pulse-Data-Visualization-and-Exploration.git

cd Guvi\_CAPSTON\_Project\_Phonepe-Pulse-Data-Visualization-and-Exploration

```



\### 2. Install Required Packages



``` bash

pip install streamlit pandas psycopg2 plotly pillow requests streamlit-option-menu

```



\### 3. Setup PostgreSQL Database



\-   Create a new database named \*\*`phonepay`\*\*.



\-   Run your table creation and data insertion scripts.



\-   Update your database credentials inside the Streamlit app:



&nbsp;   ``` python

&nbsp;   mydb = psycopg2.connect(

&nbsp;       host="localhost",

&nbsp;       user="postgres",

&nbsp;       password="your\_password",

&nbsp;       database="phonepay",

&nbsp;       port="5432"

&nbsp;   )

&nbsp;   ```



\### 4. Run the Dashboard



``` bash

streamlit run app.py

```



\*(Replace `app.py` with your actual Python file name if different.)\*



------------------------------------------------------------------------



\## 📊 Sample Visuals



\-   \*\*Bar Charts:\*\* Transaction Amounts and Counts by State\\

\-   \*\*Pie Charts:\*\* Market Share of Mobile Brands\\

\-   \*\*Choropleth Maps:\*\* State-wise Transaction Distribution\\

\-   \*\*Line Graphs:\*\* User Growth and App Opens over Time



------------------------------------------------------------------------



\## 🚀 Future Enhancements



\-   Add real-time API integration for live PhonePe data updates\\

\-   Implement machine learning to forecast transaction trends\\

\-   Integrate authentication for personalized dashboards\\

\-   Add download/export options for visual reports



------------------------------------------------------------------------



\## 👨‍💻 Author



\*\*Name:\*\* \\Alfred MV\\

\*\*Contact:\*\* \\visionwandererr@gmail.com\\

\*\*Tools Used:\*\* Python \\| PostgreSQL \\| Streamlit \\| Plotly



