# Purpose

On Friday, December 10, 2021, a tornado hit Mayfield, Kentucky and caused widespread outages. A microgrid can keep critical buildings operational during an emergency. Today, we will have an initial look at the medical infrastructure of Mayfield, Kentucky in order to set the stage for a microgrid feasibility study.

# Method

We will start by identifying critical loads that must have power during an emergency. According to [NYSERDA 17-23 Evaluation of New York Prize Stage 1 Feasibility Assessments](https://www.nyserda.ny.gov/-/media/Files/Publications/Research/Electic-Power-Delivery/17-23-Evaluation-of-New-York-Prize.ashx), critical loads include hospitals, medical centers, clinics and emergency medical care services and facilities. We searched for medical facilities manually using Google Maps.

# Results

## Hospitals and Medical Centers

A search for hospitals and medical centers produced the following results:

- [Jackson Purchase Medical Center](https://www.jacksonpurchase.com) is at Medical Center Cir, Mayfield, KY 42066.

## Clinics

A search for medical clinics produced over a hundred results. Most of the results will need to be filtered to prioritize buildings that can support many patients.

## Emergency Medical

A search for emergency medical services produced the following results:

- Jackson Purchase Medical Center: Emergency Room
- Marshall Emergency Service Associates
- Fast Pace Health
- Fresenius Medical Care at Jackson Purchase Medical
- Emergency Alert
- Air Evac 108

# Conclusion

We did an initial query of medical centers and clinics in Mayfield, Kentucky. The next step is to see if we can query medical center building locations programmatically. It seems we can do this using the [Google Places Text Search API](https://developers.google.com/maps/documentation/places/web-service/search-text). We should then screen each building by square footage and estimate peak load in kilowatts so that we can size our microgrid.
