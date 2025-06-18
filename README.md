# Excel Gantt Chart Template
A dynamic, easy-to-use Gantt chart template for project planning and tracking in Excel. This template supports multiple workstreams, auto-generates a timeline based on project dates, and visually tracks progress for each task.

![Example](/Images/Ex.jpg)

I have also remixed this into a Leave Tracker! Will share when I have the time~

## Download & Setup
**Download the file**: [Gantt Chart Template Excel](https://github.com/coolene/excel-gantt-chart/blob/main/GanttChartTemplate_Raw_v1.0.xlsx)

### Input the Project Dates
When you first open the sheet, you may notice several red boxes — these are placeholders and will disappear once you enter your project’s start and end dates in cells G1 and G2.

After entering the date range, a marker will automatically indicate today’s date on the timeline.

![DI1](/Images/DI1.jpg)
![DI2](/Images/DI2.jpg)
After inputing the date range, there will be a marker, indicating today's date.

### Configure Workstream and Team Members
To customize the dropdown menus for workstreams and team members, go to the Data Validation tab and fill in columns B (Workstreams) and F (Assignees).

These lists will populate the dropdown menus in the main task table for easy selection.


![DV](/Images/DV.jpg)

### Add Tasks
![Example](/Images/Ex.jpg)
Populate the main table with your project tasks. The Gantt chart will update automatically to reflect your entries.

 The number of days counter (Column F) does not automatically fill for new tasks, so plase use autofill from the first task item, F4.

```
=DAYS(E4,D4)+1
```

### Gantt Chart Legend
The Gantt chart uses color coding to visually represent task status based on % Progress (column G) and task dates:
| Colour | Meaning                    |
|--------|----------------------------|
| Grey   | Upcoming Task (Future)     |
| Yellow | Active Task (Not Started)  |
| Blue   | Active Task (Started)      |
| Red    | Overdue Task               |
| Green  | Completed Task             |

*Note: An “Active Task” is one where today’s date falls between the task’s start and end dates.*

## Support & Feeback
If you find this template helpful and would like to support its continued development or development of similar stuff, you can do so here: <br>

<a href='https://ko-fi.com/M4M2DDRYC' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://storage.ko-fi.com/cdn/kofi4.png?v=6' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>

If you have ideas for improvements or encounter any issues, please feel free to share them. Thank you for using this template. :D
