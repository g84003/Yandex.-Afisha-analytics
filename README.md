# Yandex.-Afisha-analytics

The project is made in order for the analytical department at Yandex.Afisha to optimize marketing expenses.
We will analyse: server logs with data on Yandex.Afisha visits from June 2017 - May 2018, dump file with all orders for the period, marketing expenses statistics.
We will study: how people use the product, when they start to buy, how much money each customer brings. We will also choose which sourse brings more money and which one should be cut off in terms of expenses


## Description of the data
The visits table (server logs with data on website visits):<br>
Uid — user's unique identifier<br>
Device — user's device<br>
Start Ts — session start date and time<br>
End Ts — session end date and time<br>
Source Id — identifier of the ad source the user came from<br>
All dates in this table are in YYYY-MM-DD format.<br>
The orders table (data on orders):<br>
Uid — unique identifier of the user making an order<br>
Buy Ts — order date and time<br>
Revenue — Yandex.Afisha's revenue from the order<br>
The costs table (data on marketing expenses):<br>
source_id — ad source identifier<br>
dt — date<br>
costs — expenses on this ad source on this day<br>
