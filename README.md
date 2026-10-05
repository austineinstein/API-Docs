# API-Docs

![This is an image](https://www.fancourier.ro/wp-content/themes/fancourier/images/logo.png)

This repository contains the FAN Courier SelfAWB API documentation, CSV templates, and example materials needed to integrate label generation, shipping workflows, and locker-based deliveries.

## What is included

The original documentation was shipped as ZIP archives. The contents have been extracted into the `docs/` folder so the files are directly browsable and usable.

- `docs/EN/` — English documentation, CSV templates, and integration examples
- `docs/RO/` — Romanian documentation, CSV templates, and integration examples
- `EN.zip` and `RO.zip` — original packaged archives retained for reference

## Quick start

1. Open the relevant folder under `docs/`.
2. Review the PDF documentation under `Integration documentation` or `API FAN Courier + FANbox`.
3. Use the CSV examples from the `Csv files` / `Fisiere csv` folders as templates for your AWB payloads.
4. Refer to the sample scripts under `Scripts examples/` for implementation examples.

## Testing credentials

These are public test credentials for validation purposes only:

- ClientID: 7032158
- Username: clienttest
- Password: testing

## Integration workflow

The standard workflow is:

1. Generate an AWB using the integration script and CSV model file
2. Print the AWB or generate the PDF output
3. Create the pickup order for courier collection
4. Calculate transport cost using the pricing endpoint or script

## Contact

For any inquiries, contact: _asistenta.it@fancourier.ro_
