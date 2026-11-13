# Production, Downtime & Equipment Performance — Power BI

Interactive Power BI dashboard for a food & beverage bottling operation:
production time, downtime, equipment utilization and failure analysis.

> **Data transparency:** This public version uses a fictional scenario and
> synthetic data. Equipment IDs, products, dates and KPI values are illustrative.
> The analytical framework, KPI selection, DAX measures, layout and design are my own work.
> It is based on a real project in which I collected shop-floor data with operators,
> supervisors and production managers, designed the data-capture file and built
> the original dashboard. No company records are published here.

![Cover](images/046D02A5-F44E-4958-8E85-80DBC5FC4631.png)

## Report pages
| Page | What it answers |
|---|---|
| Key Performance Indicators | Availability, utilization, production vs. available time, time share, downtime by reason |
| Equipment Performance | Which equipment produced most, top products/batches, utilization ranking |
| Equipment Failure Analysis | MTTR, MTBF, failure events, maintenance time by equipment and by issue |
| Production Details | Activity-level log with filters (equipment, product, activity, downtime reason) |

## KPIs
- **Utilization** = production time / total recorded time
- **Availability** = share of the time equipment should be available in which it was actually available
- **MTTR** = total maintenance time / failure events
- **MTBF** = operating time / failure events

## Data model
Star schema: one fact table of equipment activities (equipment, date, product,
activity type, batch, duration, downtime reason) with date, equipment, process
and material dimensions.

## Tools
Power BI · DAX · Data modeling

## Screenshots
### Key Performance Indicators
![KPIs](images/8A3948FE-740F-4FD2-A75F-05F0D3A3B7C1.png)

### KPI page with drill-down tooltip
![KPI tooltip](images/AE2DD316-242B-4A11-A133-0772753D40E6.png)

### Equipment Performance
![Equipment performance](images/AA347A94-63D2-4EAC-868E-35F9EDA21789.png)

### Equipment Failure Analysis
![Failure analysis](images/28FF60C5-C9AB-40DE-B787-9F142EBC6C67.png)

### Production Details
![Production details](images/624F26E6-A03A-44F4-9D10-C11DE7B09610.png)

## Contact
Faramarz Emamisaleh — Nantes, France · faramarz.emami.saleh@gmail.com · [LinkedIn](https://www.linkedin.com/in/faramarz-emamisaleh-229128b9/)
