# Welcome to BleuNova Echohub

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.


# Techinical Documentation

## Temparature control 
### Heat flow
* need to add a `metal plate` to increase heat spread.

### Control
* Change the temperature sensor to get a better reading. Replace the thermistor with LM35 and insulate properly. Use silicon or Teflon wires to withstand temperature.
* Impliment a `PID` loop to control temparature.
* replace the mechanical relay with a solid-state device. For the time being use an `Optotriac with a triac bt136` or even low power triac. The heating element takes only 40 W.
