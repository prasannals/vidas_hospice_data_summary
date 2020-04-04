# Summary of the Vidas Hospice Data

#### Tables in the data and selected important columns in each table (refer the individual table files to view all columns) - 


# care_translated

## Columns - 

#### [IDEHR](care_translated/IDEHR.md)
#### [TimeStamp_Insert](care_translated/TimeStamp_Insert.md)
#### [PatientID](care_translated/PatientID.md)
#### [ds_note_x](care_translated/ds_note_x.md) - conveys urgency and other notes
#### [opt_ausilio](care_translated/opt_ausilio.md) - beds and other equipments provided for assistance
#### [ds_altro_farmaco](care_translated/ds_altro_farmaco.md) - type of therapy given? Contains "relief cp", "oxygen therapy" "midazolam" etc.
#### [ds_dose](care_translated/ds_dose.md) - dosage (1 cp, 1 tablet etc.)
#### [opt_via_di_somm](care_translated/opt_via_di_somm.md) - describes how the drug was administered (oral, transdermal etc.)
#### [ds_note_y](care_translated/ds_note_y.md) - another note. Many notes describe under what condition the treatment (?) should be given.
#### [opt_farmaco](care_translated/opt_farmaco.md) - drug names
#### [Note_al_bisogno](care_translated/Note_al_bisogno.md) - another note that conveys the situation under which a treatment (?) should be given

[Click here](care_translated.md) to view all columns in this table

# hospice_therapy_translated

## Columns - 

#### [PatientID](hospice_therapy_translated/PatientID.md)
#### [EHRID](hospice_therapy_translated/EHRID.md)
#### [Age](hospice_therapy_translated/Age.md)
#### [Sex](hospice_therapy_translated/Sex.md)
#### [StartOfHospitalization](hospice_therapy_translated/StartOfHospitalization.md)
#### [EndOfHospitalization](hospice_therapy_translated/EndOfHospitalization.md)
#### [Diagnosis](hospice_therapy_translated/Diagnosis.md)
#### [TipeOfTherapy](hospice_therapy_translated/TipeOfTherapy.md) - contains values "Standard" and "When needed"
#### [DrugName](hospice_therapy_translated/DrugName.md) - regional drug name
#### [DrugCode](hospice_therapy_translated/DrugCode.md)
#### [ATCCode](hospice_therapy_translated/ATCCode.md)
#### [ComplementaryCodeDose](hospice_therapy_translated/ComplementaryCodeDose.md) - some sort of dosage information
#### [ActiveIngredient](hospice_therapy_translated/ActiveIngredient.md) - generic drug name
#### [Packacing](hospice_therapy_translated/Packacing.md)
#### [TypeOfUsage](hospice_therapy_translated/TypeOfUsage.md) - "transdermal", "inhalation" etc.
#### [Dose](hospice_therapy_translated/Dose.md)
#### [HoursString](hospice_therapy_translated/HoursString.md) - the time at which medicine should be administered. "8; 10; 18" means that the treatment should be given at 8 am, 10am and at 6 pm
#### [MaxDose](hospice_therapy_translated/MaxDose.md)
#### [Frequency](hospice_therapy_translated/Frequency.md)
#### [Duration](hospice_therapy_translated/Duration.md) - some sort of duration. Exact meaning still a mystery (would be helpful to find out more about this from Vidas).

[Click here](hospice_therapy_translated.md) to view all columns in this table

# input_table_translated

## Columns - 

#### [IDEHR](input_table_translated/IDEHR.md)
#### [TimeStamp_Insert](input_table_translated/TimeStamp_Insert.md)
#### [PatientID](input_table_translated/PatientID.md)
#### [EHRType](input_table_translated/EHRType.md) - "AMB" and "EHR"
#### [ds_familiari_coinv](input_table_translated/ds_familiari_coinv.md) - caregivers and/or related people
#### [Caregiver_principale](input_table_translated/Caregiver_principale.md) - caregivers and/or related people
#### [Caregiver](input_table_translated/Caregiver.md) - caregivers and/or related people
#### [persone_vicine](input_table_translated/persone_vicine.md) - caregivers and/or related people
#### [opt_consapevolezza](input_table_translated/opt_consapevolezza.md) - describes awareness of diagnosis and prognosis
#### [Perception](input_table_translated/Perception.md) - concern for health, demoralization, apathy etc.
#### [elimination](input_table_translated/elimination.md) - regarding bowel movement
#### [perc_salute](input_table_translated/perc_salute.md) - salute means "health" in Italian. Describes various health conditions. (get ready for some italian and some unknown characters)
#### [sonno_riposo](input_table_translated/sonno_riposo.md) - regarding patients sleep status
#### [cognitivo_percettivo](input_table_translated/cognitivo_percettivo.md) - "uncontrolled pain", "ideo-motor slowdown", "drowsiness" etc.
#### [nutritional](input_table_translated/nutritional.md) - "nausia", "emesis", "hiccups" etc.
#### [diagnosis](input_table_translated/diagnosis.md) - notes in Italian

[Click here](input_table_translated.md) to view all columns in this table


# outcome_death_table (Contains death info)

## Columns - 

#### [IDDecesso](outcome_death_table/IDDecesso.md)
#### [IDEHR](outcome_death_table/IDEHR.md)
#### [TimeStamp_Insert](outcome_death_table/TimeStamp_Insert.md)
#### [PatientID](outcome_death_table/PatientID.md)
#### [Date](outcome_death_table/Date.md) - this is the date and time of death
#### [Note](outcome_death_table/Note.md) 

[Click here](outcome_death_table.md) to view all columns in this table

# outcome_table

## Columns - 

#### [IDEHR](outcome_table/IDEHR.md)
#### [TimeStamp_Insert](outcome_table/TimeStamp_Insert.md)
#### [PatientID](outcome_table/PatientID.md)
#### [ds_note](outcome_table/ds_note.md)
The below four columns seem really important. But I'm not quite sure how to describe them. A doctors interpretation of these columns will be very helpful.
#### [opt_problem](outcome_table/opt_problem.md) - seems to describe problems that the patient has
#### [opt_obiettivo](outcome_table/opt_obiettivo.md)
#### [opt_stato_problema](outcome_table/opt_stato_problema.md) - status of the problem
#### [opt_interventi](outcome_table/opt_interventi.md)
Would be helpful to know what the below columns represent. They seem to be some numeric versions of the above four columns - 
#### [opt_problem_num](outcome_table/opt_problem_num.md)
#### [opt_obiettivo_num](outcome_table/opt_obiettivo_num.md)
#### [opt_stato_problema_num](outcome_table/opt_stato_problema_num.md) 
#### [opt_interventi_num](outcome_table/opt_interventi_num.md)


[Click here](outcome_table.md) to view all columns in this table


# observation_table

## Columns - 

#### [idehr](observation_table/idehr.md)
#### [timestamp_insert](observation_table/timestamp_insert.md)
#### [patientid](observation_table/patientid.md)
#### [chk_ausili_presidi](observation_table/chk_ausili_presidi.md) - aids provided for urination
Names of the below columns are self explanatory. Click on the name to view the frequently occurring values in the column.
#### [opt_hypotrophy](observation_table/opt_hypotrophy.md)
#### [opt_anxiety](observation_table/opt_anxiety.md)
#### [chk_eloquence](observation_table/chk_eloquence.md)
#### [anorexia](observation_table/anorexia.md)
#### [personal_hygiene](observation_table/personal_hygiene.md)
#### [urine_elimination](observation_table/urine_elimination.md)
#### [mobility](observation_table/mobility.md)
#### [hemorrhagic_manifestation](observation_table/hemorrhagic_manifestation.md)
#### [speech](observation_table/speech.md)
#### [cough](observation_table/cough.md)
#### [nausea](observation_table/nausea.md)
#### [memory_deficit](observation_table/memory_deficit.md)
#### [cognitive_deficit](observation_table/cognitive_deficit.md)
#### [active_diuresis](observation_table/active_diuresis.md)
#### [lack_of_appetite](observation_table/lack_of_appetite.md)
#### [opt_cooperation](observation_table/opt_cooperation.md)
#### [opt_memory_deficit_type](observation_table/opt_memory_deficit_type.md)
#### [opt_care_giver](observation_table/opt_care_giver.md)
#### [chk_gastrointestinal_symptoms](observation_table/chk_gastrointestinal_symptoms.md)
#### [chk_bowel_symptoms](observation_table/chk_bowel_symptoms.md)
#### [opt_dehydration](observation_table/opt_dehydration.md)
#### [opt_attitude](observation_table/opt_attitude.md)
#### [pain_freq](observation_table/pain_freq.md)
#### [pain_relief](observation_table/pain_relief.md)
#### [breath](observation_table/breath.md)
#### [consolability](observation_table/consolability.md)
#### [body_language](observation_table/body_language.md)
#### [facial_expression](observation_table/facial_expression.md)
#### [awareness](observation_table/awareness.md)
#### [asthenia](observation_table/asthenia.md)
#### [cachexia](observation_table/cachexia.md)
#### [dyspnoea](observation_table/dyspnoea.md)
#### [motor_performance](observation_table/motor_performance.md)
#### [body_temp](observation_table/body_temp.md)
#### [agitation_behavior_freq](observation_table/agitation_behavior_freq.md)
#### [diet](observation_table/diet.md)
#### [cognitive_state](observation_table/cognitive_state.md)
#### [feces_elimination](observation_table/feces_elimination.md)
#### [consumption_help](observation_table/consumption_help.md)
#### [mood](observation_table/mood.md)

[Click here](observation_table.md) to view all columns in this table