# Grouping-of-Minisubs-Using-Computer-vision

Grouping of minisub stations is a sub project of the MOP: Maintenance Optimisation Project

Cleaning up the mess!!!
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/a4590ffe-6e39-4cd0-824d-bda8508687b3" />


This project is an autometed approach to group mini substations that are in a ring. Grouping is done in two stages, from the SAP functional desciption and from the system diagram as shown below. The groups are grouped by the electricity load flow. The project was initiated as the data is not available in the format to implement in SAP in bulk(The data can not be found in the existing digital systems such as GIS and SCADA). The project saves more than 2 years of manual labour and can be run multple times should the system diagrms change. Below is the snapshot of the system diagrams, groups in the first picure are highlited in blocks of colour. Computer vision techniques, feature extration/engineering, template matching and a support vector machine was utilised to group from the pdf system diagrams. To summarise a custom process was desinged to make the computer understand the drawings and group.

<img width="1497" height="623" alt="image" src="https://github.com/user-attachments/assets/b19507b1-7be2-46b0-843f-6579e44b6dc1" />


<img width="1871" height="836" alt="image" src="https://github.com/user-attachments/assets/7c326cb2-5e0f-46da-a5f3-107803b310b4" />


