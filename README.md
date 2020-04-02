# ApproximateName2RxNorm

Take an approximate name of a medication concept and return the standard details of the best matching concept from RxNorm.
Note. This is a per-record solution. If you need to treat a set of many records, check out https://github.com/yumakemore/Medication2RxNorm

Byunggu Yu, Ph.D.

April 1, 2020

Given an approximate medication concept name, this program finds the best matching concept from RxNorm and returns the details such as standard codes, standard name, dossage, etc.

Example:

Input:

zocor 10 mg

Output:

RxNorm ApproximateTerm Score = 75

TTY = SBD

PRESCRIBABLE = Y

HUMAN_DRUG = US

SCHEDULE = 0

AVAILABLE_STRENGTH = 10 MG

GENERAL_CARDINALITY = SINGLE

RxCUI = 104490

NDA = NDA019766

UMLSCUI = C0354662

MMSL_CODE = BD3081

SPL_SET_ID = fdbfe194-b845-42c5-bb87-a48118bc72e7

RxNorm Name = Simvastatin 10 MG Oral Tablet [Zocor]

RxNorm Synonym = Zocor 10 MG Oral Tablet

Prescribable Synonym = Zocor 10 MG Oral Tablet

Source = Gold Standard Alchemy

Source = Multum MediSource Lexicon

Source = Micromedex RED BOOK

Source = Metathesaurus FDA Structured Product Labels
