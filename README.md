Supply Chain Performance & Predictive Analytics

What was the problem?

I looked at data from over 180,000 online orders and noticed something worrying — more than half of them (54.7%) were arriving late. That kind of delay was putting around $2.1 million of the company's profit at risk. I wanted to figure out why this was happening and see if I could predict which orders were likely to be late before they even shipped.

What I did.

Cleaned and explored the whole dataset using Python (Pandas and NumPy) to spot patterns.
Dug into the "why" behind the delays, and found three big culprits:
Orders sent using First-Class shipping
Deliveries going to Central Africa
Orders placed during the December holiday rush
Since "late orders" were a small part of the dataset compared to "on-time orders," I used a technique called SMOTE to balance things out so the model wouldn't ignore the late ones.
Built a Random Forest model — basically a smart prediction system — to flag risky orders at checkout.
Made charts with Matplotlib and Seaborn to show the delay patterns clearly.

What I found.

The model could correctly spot high-risk late orders 74% of the time. More importantly, I found three clear, real reasons for the delays that a business could actually act on — like rethinking First-Class shipping routes or planning better for the holiday rush.

Tools I used
Python, Pandas, NumPy, SMOTE, Scikit-learn, Matplotlib, Seaborn, Jupyter Notebook.
