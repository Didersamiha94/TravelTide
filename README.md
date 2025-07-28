# TravelTide Rewards Optimization

## Enhancing Customer Loyalty Through Data-Driven Segmentation

Welcome to the **TravelTide Rewards Program** project! This repository documents the end-to-end analytics project focused on segmenting users and assigning personalized perks based on their booking behavior. By leveraging SQL, Tableau, and thoughtful segmentation, the goal is to enhance customer retention and increase revenue.

---

## 📁 Project Structure

This repository is organized into the following directories:

### `/sql`
Contains all SQL queries used for:
- Cohort filtering
- Session and trip aggregation
- Customer segmentation
- Perk assignment logic

### `/data`
Includes the main dataset (`users_rewards.csv`) exported from the database containing:
- Demographics
- Travel behavior
- Perk assignments

### `/dashboard`
Contains Tableau workbook screenshots and links to:
- Segmentation and Perk distribution
- Segment based Travel patterns and discounts
- Demographic analysis

Live dashboard on Tableau Public 👉 [View Dashboard](https://public.tableau.com/views/Traveltide_17536644382430/Story1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

### `/presentation`
Includes the video presentation (`.mp4`) that walks through:
- Business problem
- SQL approach
- Segmentation logic
- Dashboard insights and recommendations

---

## ✈️ Customer Segments

Users were segmented based on booking behavior, family status, budget sensitivity, and travel spontaneity. The final segmentation includes:

| Segment Name               | Description |
|---------------------------|-------------|
| **Frequent Travellers**   | Users with 4+ trips and low cancellation behavior |
| **Family-Oriented Travellers** | Booked hotels with >1 room and stayed longer than 3 days |
| **High-Spending Travellers** | Spent over $1500 on flights or $1000 on hotels |
| **Budget Travellers**     | Used flight or hotel discounts frequently |
| **Spontaneous Travellers** | Booked trips with <7 days to departure |
| **Moderate Travellers**   | Booked 3+ trips or had low cancellation rate |
| **Occasional Travellers** | Default group when no other criteria were met |

---

## 🎁 Perk Assignment

Each group received personalized perks:

| Segment | Perk |
|--------|------|
| Family-Oriented Travellers | Free checked bag |
| High-Spending Travellers   | Free hotel meal |
| Budget Travellers          | Exclusive discounts |
| Frequent Travellers        | 1 night free hotel with flight |
| Spontaneous Travellers     | No cancellation fees |
| Moderate Travellers        | Priority boarding |
| Occasional Travellers      | Loyalty points |

---

## ✅ Project Outcomes

- Built a behavioral cohort of engaged users
- Replaced incomplete or dirty values (e.g., negative hotel nights)
- Segmented 7 unique user personas
- Assigned targeted perks for each group
- Created an interactive Tableau dashboard
- Presented a concise executive summary and stakeholder video

---

## 🚀 Next Steps

1. **Deploy Rewards Program** based on final assignments.
2. **Monitor Perk Engagement** through future usage logs.
3. **A/B Test Offers** to optimize rewards across segments.
4. **Refine Segments** as more behavioral data is collected.

---

## 🙌 Acknowledgements

Special thanks to the stakeholders and marketing leads at TravelTide for their guidance. This project is a part of an applied analytics case study designed for real-world strategic impact.
