# infantMortalityRateMali

Variable rawDataIMR = The raw data on infant mortality rates in Mali, sourced from the St. Louis FRED 
                      https://research.stlouisfed.org/fred2/series/SPDYNIMRTINMLI

Variable IMRArray = The 'big' array of arrays. It sits outside of the 'for' loop and is referenced in data.addRows.

Variable dateAndValueArray = This is the 'medium' array within the 'for'loop. It will be populated the dates and values from rawDataIMR.
