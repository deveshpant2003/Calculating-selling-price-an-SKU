# Calculating selling price for an SKU
I have demonstrated how one can calculate the selling price for SKUs (Stock Keeping Units) using Excel. The Excel workbook contains the details for all four SKUs. The objective is to calculate the selling price for each SKU, ensuring that we achieve a net margin of 15% (margin = selling price – all expenses). I have derived all the answers via formulae. No formulae are hardcoded.  

The following formula is used in calculation of selling price:  

  
$$
\frac{\text{Storage Fee} \ + \ \text{Buying Price} \ + \ \text{Closing Fee}}
{\text{Net Margin Rate} \ + \ \text{Channel Commission Rate} \ + \ \text{Returns Rate}}
$$

## Derivation of the formula
To derive the formula for the Selling Price (𝑆𝑃) of an SKU, let’s break it down step-by-step based on the given terms:

### Terms and Variables:
**Storage Fee (𝑆𝐹):** The cost of storing the SKU. 

**Buying Price (𝐵𝑃):** The cost to procure the SKU.  

**Closing Fee (𝐶𝐹):** Any fixed cost incurred while completing the sale.  

**Net Margin (𝑁𝑀%=𝑁𝑀/100):** The desired profit margin expressed as a percentage of the Selling Price.  

**Channel Commission (𝐶𝐶%=𝐶𝐶/100):** The percentage commission charged by the sales channel.  

**Returns (𝑅%=𝑅/100):** The expected percentage of returned items relative to the Selling Price.  

**Selling Price (𝑆𝑃):** The price at which the SKU is sold to achieve the desired profit margin.

### Revenue (Selling Price - Costs)
The Selling Price must cover all the associated costs and margins. Therefore:  

𝑆𝑃 = Costs + Profit Margin  

#### Costs Breakdown
The total cost includes:  

Costs = 𝑆𝐹 + 𝐵𝑃 +𝐶𝐹  

#### Profit Margin:  
The profit margin is calculated as a percentage (𝑁𝑀%) of the Selling Price:  

Profit Margin = 𝑁𝑀% ⋅ 𝑆𝑃  
  
#### Other Adjustments:
The Selling Price also accounts for:  
  
**Channel Commission:** Charged as 𝐶𝐶% ⋅ 𝑆𝑃.  
  
**Returns:** Accounted as 𝑅% ⋅ 𝑆𝑃.  
  
Thus, the Selling Price must cover not only the costs and profit margin but also these percentage-based charges.

#### Full Equation
The Selling Price is:  

𝑆𝑃 = Costs + 𝑁𝑀% ⋅ 𝑆𝑃 + 𝐶𝐶% ⋅ 𝑆𝑃 + 𝑅% ⋅ 𝑆𝑃  
  
Substitute Costs:  
𝑆𝑃=(𝑆𝐹 + 𝐵𝑃 + 𝐶𝐹) + (𝑁𝑀% + 𝐶𝐶% + 𝑅%) ⋅ 𝑆𝑃  

 #### Isolate Selling Price (𝑆𝑃)

 Rearrange to solve for 𝑆𝑃:  
𝑆𝑃 −(𝑁𝑀% + 𝐶𝐶% + 𝑅%) ⋅ 𝑆𝑃 = 𝑆𝐹 + 𝐵𝑃 + 𝐶𝐹  

Factorize 𝑆𝑃:  
𝑆𝑃 ⋅ (1 − (𝑁
𝑀
%
+
𝐶
𝐶
%
+
𝑅
%
)
)
=
𝑆
𝐹
+
𝐵
𝑃
+
𝐶
𝐹
SP⋅(1−(NM%+CC%+R%))=SF+BP+CF
Finally, divide both sides by 
(
1
−
(
𝑁
𝑀
%
+
𝐶
𝐶
%
+
𝑅
%
)
)
(1−(NM%+CC%+R%)):

