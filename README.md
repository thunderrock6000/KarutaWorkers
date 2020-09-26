# KarutaWorkers
A combination of Calculators and Organizational tools for easy tracking of Karuta workers

# Calculator
By default this sheet is locked (no password) except for cells highlighted in bright yellow to prevent accidental modification of formulas and references.
Six calculators are currently supported: 1 Mint Effort, 2 Healthy Effort, and 3 Dye/Framing Effort (Mystic Dye is not yet supported)

# Workers (Distribution Copy)
## Syntax
"Name", "Series", and "Card ID" are solely for the user to identify and find their workers once input.
"Quality" (as an integer from 0 to 4) is used in later formulas to calculate a card's expected mint effort.
"Number" (referring to print number) is not used in any formula, but is retained due to its usefullness in organization.
## Injuries
"Status" and "Recov." are formula cells and will update to reflect injury status.
"Date" and "Length" feed the Status and Recov. formulas and thus should be blank unless a card is injured.
## Effort
"Expected Basic Effort" is the un-dyed and un-framed effort a card is expected to have once mint (This is used to identify cards which benefit most from dye and frames)
"Expected (Healthy)" only differs from "Expected Basic Effort" if a card has been dyed or framed, and thus is used to sort cards by their real mint effort values
"Actual Effort" is the current effort of a card (not the expected mint effort, but still impacted by injury status) and thus is used to identify workers for jobboards

# Growth Data & Raw Data
By default these sheets are locked (no password) to prevent accidental influence to calculators and worker listings
These sheets host the data from which all calculations are based on
