This project demonstrates data visualization in Tableau and logical data transformation in Excel.

## 📊 Tableau: Downtime Analysis
**Objective:** Calculate and visualize potential downtime from equipment telemetry logs.

### Key Technical Steps:
* **Custom Measure:** Created an `Unhealthy` field to represent 10-minute intervals of downtime.
* **Logic:** `IF [Status] = "Unhealthy" THEN 10 ELSE 0 END`
* **Interactive Dashboard:** Built a "Factory-to-Device" filter. Selecting a factory instantly updates the device-specific downtime.

![Downtime Dashboard](Screenshot 2026-04-01 125948.png)

## 📈 Excel: Equality Classification
**Objective:** Automate the categorization of employee equality scores using nested logic.

### Logic Applied:
* **Fair:** +/- 10
* **Unfair:** Beyond +/- 10
* **Highly Discriminative:** Beyond +/- 20

![Equality Table](Screenshot 2026-04-01 140713.png)
