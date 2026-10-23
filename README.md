# EasyDentalLab Price Lists

Official tariff codes and medical aid lists for EasyDentalLab.

## Files

- `Tariffs-2027.csv` - Default tariff codes and prices
- `MedicalAids-2027.csv` - List of medical aids (name and plans)
- `version.json` - Version metadata for auto-update system

## Usage

This repository is automatically checked by EasyDentalLab for price updates.

Users can also manually download and import these files via the app's "Import from File" feature.

## Format

### Tariffs-2027.csv
```csv
UserCode,TariffCode,Description,DescriptionAFR,Category,Measure,Price
9600,9600,Crown per unit,Kroon per eenheid,Crown & Bridge,each,1500
```

### MedicalAids-2027.csv
```csv
MedicalAid,Plan
Discovery Health,KeyCare Plus
Discovery Health,Classic Smart
Bonitas,BonCap
```

