For preprocessing, I first made sure all the features were in the right data types so everything lines up properly. Order ID was set as the primary key since it’s the only unique feature, and no duplicates showed up. The only missing values were in the Promotion column (370 entries), so I filled those in as “No Promotion.” I also checked for invalid values like negatives, but none were found.

When I ran outlier detection with the IQR method, 17 outliers popped up in Total Price. After double‑checking, they turned out to be legitimate transactions, for example, ₱576.3 discounted at 0.05 correctly becomes ₱547.485, and ₱10,949.7 matches the recorded total price, so I kept them. 

<p align = "center">
  <img width="732" height="266" alt="image" src="https://github.com/user-attachments/assets/167a730e-3649-40e8-9b69-f670c346765a" />
</p>

Finally, I scanned for inconsistencies like misspellings or unexpected values like the one below, and everything looked clean.
<p align = "center">
  <img width="225" height="215" alt="image" src="https://github.com/user-attachments/assets/e0399873-2d30-482e-a7e3-aa13453d0526" />
</p>

