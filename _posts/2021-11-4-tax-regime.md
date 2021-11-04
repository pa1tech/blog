---
layout: post
title: "#6 What's the catch in the old vs new regime slabs?"
avatar: "/images/3_income_tax.jpg"
---

I am sure most of the salaried employees, after coming accross the tax slab rates in the old and new tax regimes, would have used some online calculators to decide which regime gives them lesser tax liability. But can we decide on a regime without any math?

<br/>
<div style="text-align:center"><img src="{{ site.baseurl }}/images/3_income_tax.jpg" /></div>
<br/>

> What is the logic behind those slab rates? (Is there a logic at all?) <br/> <br/>
> I feel old tax regime **always** gives lesser tax liability (given a very few conditions)

Let's get into the elaboration of the above lines.

### The Slab Table

<table>
<thead>
  <tr>
    <th>Tax Slab</th>
    <th>New Regime (%)</th>
    <th>Old Regime (%)</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>0 - 2.5L</td>
    <td>0</td>
    <td>0</td>
  </tr>
  <tr>
    <td>2.5L - 5L</td>
    <td>5</td>
    <td>5</td>
  </tr>
  <tr>
    <td>5L - 7.5L</td>
    <td>10</td>
    <td>20</td>
  </tr>
  <tr>
    <td>7.5L - 10L</td>
    <td>15</td>
    <td>20</td>
  </tr>
  <tr>
    <td>10L - 12.5L</td>
    <td>20</td>
    <td>30</td>
  </tr>
  <tr>
    <td>12.5L - 15L</td>
    <td>25</td>
    <td>30</td>
  </tr>
  <tr>
    <td>15L and above</td>
    <td>30</td>
    <td>30</td>
  </tr>
</tbody>
</table>

Since slabs are defined for every 2.5L, I will assume a gross salary which is a multiple of 2.5L.

### A Closer Look at the Slab rates
Let's compute the tax liability for different taxable incomes(gross-deductions). Since I am making the 2.5L multiple assumption, computation becomes easy. We just have to add up all the tax percentages till our assumed income and multiply by 2.5L.

For example, a net taxable income of 10L in old regime is liable to (5%+20%+20%) = 45% of 2.5L = 1.125L.The same in the new ta regime will be (5%+10%+15%) = 30% of 2.5L = 0.75L

<table>
<thead>
  <tr>
    <th>Gross Taxable Income</th>
    <th>New Regime<br>(% of 2.5L)</th>
    <th>Old Regime<br>(% of 2.5L)</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>5L</td>
    <td>5</td>
    <td>5</td>
  </tr>
  <tr>
    <td>7.5L</td>
    <td>15</td>
    <td>25</td>
  </tr>
  <tr>
    <td>10L</td>
    <td>30</td>
    <td>45</td>
  </tr>
  <tr>
    <td>12.5L</td>
    <td>50</td>
    <td>75</td>
  </tr>
  <tr>
    <td>15L</td>
    <td>75</td>
    <td>105</td>
  </tr>
  <tr>
    <td>17.5L</td>
    <td>105</td>
    <td>135</td>
  </tr>
  <tr>
    <td>20L</td>
    <td>135</td>
    <td>165</td>
  </tr>
</tbody>
</table>

From 12.5L, we can clearly observe one slab offset between the liability in the old and the new regimes, i.e, a gross taxable income of 12.5L in the old tax regime has the same liability as to a gross taxable income of 15L in the new tax regime!

### Deductions of 2.5L in Old Regime
* Standard Deduction - 0.5L
* 80C - 1.5L (Statutory PF, VPF, LIC, ELSS, NPS, Tax Saver Deposit Schemes,...)
* 80CCD(1B) - 0.5L (NPS contrib after 1.5L of 80C is fulfilled)

These are the investments under Section 80, which I feel IT dept would have assumed reasonable for the 2.5L offset.

Beyond 80C, the old regime provides exemption of meal tokens upto Rs.50 per meal. This aggregates to 36K per year. There are also provisons for LTA in the old regime.

So this makes me say that old regime is always better in the >12.5L income group

### Investments vs No Investment

<table>
<thead>
  <tr>
    <th>Gross Taxable Income<br>in the new regime</th>
    <th>New Regime<br>(% of 2.5L)</th>
    <th>Old Regime<br>with 1L deductions<br>(% of 2.5L)</th>
    <th>Old Regime<br>with 2.5L deductions<br>(% of 2.5L)</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>5L</td>
    <td>5</td>
    <td>3</td>
    <td>0</td>
  </tr>
  <tr>
    <td>7.5L</td>
    <td>15</td>
    <td>17</td>
    <td>5</td>
  </tr>
  <tr>
    <td>10L</td>
    <td>30</td>
    <td>37</td>
    <td>25</td>
  </tr>
  <tr>
    <td>12.5L</td>
    <td>50</td>
    <td>63</td>
    <td>45</td>
  </tr>
  <tr>
    <td>15L</td>
    <td>75</td>
    <td>93</td>
    <td>75</td>
  </tr>
  <tr>
    <td>17.5L</td>
    <td>105</td>
    <td>123</td>
    <td>105</td>
  </tr>
  <tr>
    <td>20L</td>
    <td>135</td>
    <td>153</td>
    <td>135</td>
  </tr>
</tbody>
</table>

The above two cases assumed in old regime are the extremes with 1L deductions(50K standard + 50K PF) and 2.5L deductions

Below 7.5L, assuming that the old regime always has 2.5L more deductions than the new regime, we see that old regime is always better than the new regime. But it is not reasonable to assume that a person earning 7.5L would invest/save 1.5L a year. So for below 7.5L income, calculations are a must based on their investments/savings. 


In conclusion the govt is aiding the people who can't invest/save due to high expenses(loans,EMIs,..) by introducing the new regime. With new regime people who don't invest/save are not being penalised heavily , which is the case in the old regime. 