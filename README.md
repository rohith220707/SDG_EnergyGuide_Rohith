# Energy Guide

AI chatbot project by Rohith for UN SDG 7, Target 7.3. Open
EnergyGuide_Rohith.html in a current browser. No server, API key, account,
or internet connection is required.

## Try the chatbot

- Ask about LED lighting, television standby power, cooling, or cold washes.
- Select **Estimate appliance use**. Enter **75 W**, then **6 hours**.
  The estimate is 0.45 kWh per day and 13.5 kWh over 30 days.
- Enter an unsupported question such as **Tell me a joke** to see the fallback.
- Type **cancel** during an estimate or select **New chat** to reset.

## How it works

Plain HTML, CSS and JavaScript. An example-based classifier uses binary
cosine similarity across 30 labelled examples. Below 0.38 it abstains, and
a lead below 0.10 asks for clarification. The calculator uses watts divided
by 1,000 times hours per day. It assumes constant power and stable runtime.
Chat history stays in page memory and clears on reload.

## Files

- [Rohith’s GitHub repository](https://github.com/rohith220707/SDG_EnergyGuide_Rohith)
- EnergyGuide_Rohith.html — standalone app and editable source
- SDG_EnergyGuide_Rohith.pdf — submission report
- screenshots/ — five images captured from the working browser interface
- LICENSE — MIT license

## References

- United Nations SDG 7: https://sdgs.un.org/goals/goal7
- U.S. Department of Energy guide: https://www.energy.gov/sites/default/files/2022-08/energy-saver-guide-2022.pdf
