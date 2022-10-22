# Project Title: Forecasting Net Prophet

This project includes a Jupyter notebook that contains the following: visual depictions of seasonality (as measured by Google Search traffic) that are of interest to the company, an evaluation of how the company’s stock price correlates to its Google Search traffic, a Prophet forecast model that can predict hourly user search traffic, and a plot of a forecast for the company’s future revenue.


Dataset:
---
google_hourly_search_trends.csv

mercado_daily_revenue.csv

mercado_stock_price.csv

Final Analysis:
---

The Google search traffic increased during the month of May when MercadoLibre released its financial results.
![image](https://user-images.githubusercontent.com/34729547/197365777-60493f84-e44e-48f4-82f4-0d7126891adf.png)

The search traffic tends to increase during the winter holiday period (weeks 40 through 52) with it's highest peak around week 51.
![image](https://user-images.githubusercontent.com/34729547/197365832-42b987ea-a32a-4191-8b19-fe73a8809ec2.png)

A predictable relationship exists between the lagged search traffic and the stock volatility as well as stock price returns.
![image](https://user-images.githubusercontent.com/34729547/197365914-58a4482f-6624-4b3d-8f91-e86b400295f2.png)

The best time of day for MercadoLibre is midnight.
![image](https://user-images.githubusercontent.com/34729547/197365978-1edbb05b-7dcd-4705-a8dd-2148ddac83be.png)

Tuesday is the best day of the week for search traffic.
![image](https://user-images.githubusercontent.com/34729547/197365971-c368b510-5a15-441d-9374-b2344f682acb.png)

The lowest search traffic occurs around the end of October and the beginning of November.
![image](https://user-images.githubusercontent.com/34729547/197365998-e35778c4-07b8-45d3-bcee-0d7e1463d456.png)

Based on the forecast information below, the best case scenario for future sales in the next 90 days is $24,674,677,254 (USD). The worst case scenario for future sales in the next 90 days is $20,829,059,774 (USD). Overall, the most likely scenario for future sales in the next 90 days will produce approximately $22,750,074,002 (USD)
![image](https://user-images.githubusercontent.com/34729547/197366215-39135fee-aa58-4f11-a00f-aefd78818414.png)

---

## Technologies: Python 3, Jupyter Notebook, Google Colab
---
Python 3 or later.

Jupyter Notebook for code.

Google Colab for IDE.

---

## Usage:
---

Ensure the proper libraries and dependencies have been imported.

![image](https://user-images.githubusercontent.com/34729547/197366349-a9c6b498-5db8-4eef-bbde-6a3711175eb9.png)

![image](https://user-images.githubusercontent.com/34729547/197366360-04b3a8ea-8cce-4210-ae44-5d0bf5bccbce.png)


---

## Contributors: Nia Robinson

LinkedIn: https://www.linkedin.com/in/niaelanrobinson/

---

## License

MIT License.
