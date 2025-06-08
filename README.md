# SmartAid: AI-Powered Mental Health First Aid Advisor

Final project for the Building AI course

## Summary

SmartAid är en AI-driven första hjälpen-rådgivare för psykisk hälsa som hjälper människor att hantera stress, ångest och nedstämdhet i vardagen – innan det blir ett akut problem.

## Background

Psykisk ohälsa är ett växande problem över hela världen. Många upplever symptom som ångest, stress eller nedstämdhet men vet inte vart de ska vända sig – eller känner skam att söka hjälp. Det är särskilt vanligt bland unga och i samhällen med brist på tillgång till psykologisk vård.

Min motivation är att öka tillgången till lågtröskelhjälp för psykisk hälsa med hjälp av AI. Tanken är inte att ersätta terapi, utan att erbjuda ett första stöd – som ett “digitalt trygghetsnät” dygnet runt.

Problem som löses:
* Låg tillgång till psykisk hälsa-stöd i tidiga stadier
* Skamkänslor kring att söka hjälp
* Låg kunskap om vad som är normalt och när man ska söka vård

## How is it used?

SmartAid används via en app eller webbplattform. Användaren skriver (eller pratar) in hur de mår. AI:n analyserar texten, ger empatisk respons, och föreslår konkreta övningar: andningsteknik, mindfulness, problemlösning eller sömnråd. Vid behov uppmanas användaren att kontakta vårdpersonal, och AI:n kan ge kontaktinformation till närliggande hjälpinstanser.

**Användare:** unga vuxna, studenter, vårdanställda, personer med låg tillgång till terapi  
**Behov:** låg tröskel, integritet, snabb respons, empatiskt språk

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/17/Neural_network.svg/640px-Neural_network.svg.png" width="400">

## Data sources and AI methods

AI:n tränas på:
- Öppna databaser med samtalstext (t.ex. [Mental Health Reddit Dataset](https://huggingface.co/datasets/mental_health))
- Kliniskt godkända frågeformulär (PHQ-9, GAD-7)
- Textklassificering för att upptäcka risknivåer (NLP-modeller liknande BERT eller GPT)

Möjliga metoder:
- NLP (sentimentanalys, emotion detection)
- Reinforcement Learning for suggestions
- Explainable AI (för att visa varför AI:n ger en viss rekommendation)

## Challenges

SmartAid kan inte ersätta professionell vård. Det finns risk för:
- Felbedömning av allvarliga fall
- Falsk trygghet
- Dataintegritet och sekretess måste prioriteras

Etiska överväganden:
- Tydlig kommunikation: AI:n är inte en terapeut
- GDPR-efterlevnad
- Bias i träningsdata måste undvikas

## What next?

Projektet kan växa till en fullfjädrad open source-plattform med:
- Flerspråkigt stöd
- API för integration i andra vårdsystem
- Partnerskap med skolor, företag och vårdcentraler

Behov för vidareutveckling:
- Samarbete med psykologer
- Fler datakällor
- Feedback från användare i olika samhällsgrupper

## Acknowledgments

* [Mental Health Reddit Dataset](https://huggingface.co/datasets/mental_health)
* Inspiration från Mindler, KBT-online och Replika.ai
* Icon: [Neural Network Diagram – Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Neural_network.svg) / Public Domain
# My-new-projekt
AI-projekt
