
# Intro tutorial to data.table main features

### General comments
The idea of this project is to show the main features of data.table which I believe will cover most of the data manipulation operations.

`data.table` is known because of it's speed but I would also argue it's syntax is extremely clear once understood. 
I personally found it was simpler to learn DT than R-Base for most data manipulation operations but I would still recommend beginners to 
learn R-Base first and then dive in other libraries.

I've been using DT for around 5 years and I use it exclusively for my work. I'm not an expert on the package in every sense
so I'll be talking from my experience from a user standpoint. 
Feel free to make github issues or PR in order to make improvements to the code and add other relevant points. 

### Finance Project demo.

I've downloaded some financial data of ~20000 companies for this demo. The idea is to work with real data and show how DT scales
with small/medium sized dataset. (around 2 GB).
There is a smaller version of the dataset here that has 450 MB if your RAM isn't enough for the full data.

