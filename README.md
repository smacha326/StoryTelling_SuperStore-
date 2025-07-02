# StoryTelling_SuperStore-
This was a Storytelling project that I created using simulated data during my time as a BIA trainee with TripleTen
##  Part 1: Finding the Root Causes of Returns

First, I joined the Returns table with the Orders table so I could compare which products were returned and which weren’t.

### What I did:
- Created a field where:
  - `Yes = 1` (returned)
  - `null = 0` (not returned)
- Used this to calculate **return rates** and **total returns**

### Charts I created:
1. **Scatterplot** – Compared total sales vs. total returns by product subcategory  
   → Do higher sales always mean more returns?

2. **Bar chart** – Return rate by product category  
   → Which product types are returned the most?

3. **Customer chart** – Return rate by customer (filtered to only customers with 2+ orders)  
   → Who’s returning the most?

4. **Map** – Return rate by state  
   → Are some areas returning more than others?

5. **Line chart** – Return rate by month  
   → Is there a seasonal trend?

6. **Composite visuals** – Mixes of geography + category, and time + subcategory  
   → To see patterns across more than one factor

---

## 📊 Part 2: Building the Dashboard

To pull everything together, I made a dashboard in Tableau to explore return behavior.

### Steps I followed:
- Sketched out 3 layout ideas on paper
- Chose one and created a template in Tableau using containers
- Added my charts and visuals into the dashboard
- Added filters, titles, and tooltips to make it easy to use

The goal was to make it clear and helpful for someone who wants to figure out **why returns are happening and what to do about them**.

---

##  Part 3: Telling the Story

I turned my analysis into a Tableau Story — kind of like a slideshow — to explain what I found.

### What’s included:
- Summary of the return problem
- Why I used return rate (vs. total returns or cost)
- Main causes of returns I discovered
- Breakdown of what each chart shows and how to use it
- Steps the store can take (like investigating top returners or problem products)
- A conclusion with next steps — like using the dashboard going forward

<iframe
  src="https://public.tableau.com/views/Storytelling_17462125597080/Storyboard?:embed=y&:showVizHome=no"
  width="1000"
  height="800"
  frameborder="0"
  allowfullscreen>
</iframe>

---

## Tools I Used
- Tableau (for analysis and dashboard)
- Google Sheets / Excel (for cleaning data)
- QuickTime (for screen recording the presentation)
