# Summary of the Vidas Hospice Data

#### Tables in the data and selected important columns in each table (refer the individual table files to view all columns) - 


# care_translated

## Columns - 

### [IDEHR](care_translated/IDEHR.md)
### [TimeStamp_Insert](care_translated/TimeStamp_Insert.md)
### [PatientID](care_translated/PatientID.md)
### [ds_note_x](care_translated/ds_note_x.md) - conveys urgency and other notes
### [opt_ausilio](care_translated/opt_ausilio.md) - beds and other equipments provided for assistance
### [ds_altro_farmaco](care_translated/ds_altro_farmaco.md) - type of therapy given? Contains "relief cp", "oxygen therapy" "midazolam" etc.
### [ds_dose](care_translated/ds_dose.md) - dosage (1 cp, 1 tablet etc.)
### [opt_via_di_somm](care_translated/opt_via_di_somm.md) - describes how the drug was administered (oral, transdermal etc.)
### [ds_note_y](care_translated/ds_note_y.md) - another note. Many notes describe under what condition the treatment (?) should be given.
### [opt_farmaco](care_translated/opt_farmaco.md) - drug names
### [Note_al_bisogno](care_translated/Note_al_bisogno.md) - another note that conveys the situation under which a treatment (?) should be given

[Click here](care_translated.md) to view all columns in this table

# hospice_therapy_translated

## Columns - 

### [PatientID](hospice_therapy_translated/PatientID.md)
### [EHRID](hospice_therapy_translated/EHRID.md)
### [Age](hospice_therapy_translated/Age.md)
### [Sex](hospice_therapy_translated/Sex.md)
### [StartOfHospitalization](hospice_therapy_translated/StartOfHospitalization.md)
### [EndOfHospitalization](hospice_therapy_translated/EndOfHospitalization.md)
### [Diagnosis](hospice_therapy_translated/Diagnosis.md)
### [TipeOfTherapy](hospice_therapy_translated/TipeOfTherapy.md) - contains values "Standard" and "When needed"
### [DrugName](hospice_therapy_translated/DrugName.md) - regional drug name
### [DrugCode](hospice_therapy_translated/DrugCode.md)
### [ATCCode](hospice_therapy_translated/ATCCode.md)
### [ComplementaryCodeDose](hospice_therapy_translated/ComplementaryCodeDose.md) - some sort of dosage information
### [ActiveIngredient](hospice_therapy_translated/ActiveIngredient.md) - generic drug name
### [Packacing](hospice_therapy_translated/Packacing.md)
### [TypeOfUsage](hospice_therapy_translated/TypeOfUsage.md) - "transdermal", "inhalation" etc.
### [Dose](hospice_therapy_translated/Dose.md)
### [HoursString](hospice_therapy_translated/HoursString.md) - the time at which medicine should be administered. "8; 10; 18" means that the treatment should be given at 8 am, 10am and at 6 pm
### [MaxDose](hospice_therapy_translated/MaxDose.md)
### [Frequency](hospice_therapy_translated/Frequency.md)
### [Duration](hospice_therapy_translated/Duration.md) - some sort of duration. Exact meaning still a mystery (would be helpful to find out more about this from Vidas).

[Click here](hospice_therapy_translated.md) to view all columns in this table

# input_table_translated

## Columns - 

### [IDEHR](input_table_translated/IDEHR.md)
### [TimeStamp_Insert](input_table_translated/TimeStamp_Insert.md)
### [PatientID](input_table_translated/PatientID.md)
### [EHRType](input_table_translated/EHRType.md) - "AMB" and "EHR"
### [ds_familiari_coinv](input_table_translated/ds_familiari_coinv.md) - caregivers and/or related people
### [Caregiver_principale](input_table_translated/Caregiver_principale.md) - caregivers and/or related people
### [Caregiver](input_table_translated/Caregiver.md) - caregivers and/or related people
### [persone_vicine](input_table_translated/persone_vicine.md) - caregivers and/or related people
### [opt_consapevolezza](input_table_translated/opt_consapevolezza.md) - describes awareness of diagnosis and prognosis
### [Perception](input_table_translated/Perception.md) - concern for health, demoralization, apathy etc.
### [elimination](input_table_translated/elimination.md) - regarding bowel movement
### [perc_salute](input_table_translated/perc_salute.md) - salute means "health" in Italian. Describes various health conditions. (get ready for some italian and some unknown characters)
### [sonno_riposo](input_table_translated/sonno_riposo.md) - regarding patients sleep status
### [cognitivo_percettivo](input_table_translated/cognitivo_percettivo.md) - "uncontrolled pain", "ideo-motor slowdown", "drowsiness" etc.
### [nutritional](input_table_translated/nutritional.md) - "nausia", "emesis", "hiccups" etc.
### [diagnosis](input_table_translated/diagnosis.md) - notes in Italian

[Click here](input_table_translated.md) to view all columns in this table


