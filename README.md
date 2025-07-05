# 🩺 FHIR Project: Child Immunization in Nepal

This project demonstrates how to model childhood immunization data using the **HL7 FHIR (Fast Healthcare Interoperability Resources)** standard. It focuses on creating **custom StructureDefinitions (FHIR profiles)** and sample resource instances specific to child immunization practices in Nepal.

---

## 📂 Repository Structure

FHIR-Project-Immunization/
├── Structure_Def/
│ ├── patientStructure.json
│ └── immunizationStructure.json
│ └── ImmunizationStructureDef.xslx
├── instances/
│ ├── patient.json
│ └── BCGVaccine.json
├── README.md


---

## ✅ Features

- ✅ **Custom FHIR Profile for Patient**
  - Tailored for child immunization demographic data in Nepal.
  - Includes extensions for ethnicity, and weight of child.

- ✅ **Custom FHIR Profile for Immunization**
  - Built specifically for childhood vaccines like BCG.

- ✅ **FHIR Instances**
  - Example Patient resource with demographic fields.
  - Example Immunization resource for **BCG vaccine**.

---

## 📌 Use Cases

This project can be used for:

- Academic and research purposes.
- Building FHIR-based immunization registries.
- Integrating with national systems (e.g., DHIS2, OpenIMIS).
- Demonstrating FHIR profiling and instance generation.

---

## 🧪 Tools & Standards

- **FHIR Version:** R4 (4.0.1)
- **FHIR Validator:** [HAPI FHIR Validator](https://hapifhir.io/)
- **Code System:** WHO EPI/Nepal Vaccine Codes (CVX/SNOMED if applicable)

---

## 🚀 Future Enhancements

- Add support for additional vaccines (Pentavalent, OPV, MR, JE, etc.)
- Include full immunization Bundle example.
- Build SMART dashboard using Python or React.
- Validate profiles using CI/CD GitHub Actions.

---

## 📚 References

- [HL7 FHIR Specification (R4)](https://hl7.org/fhir/)
- [FHIR StructureDefinition Guide](https://www.hl7.org/fhir/profiling.html)
- [HL7 FHIR Patient Resource](https://hl7.org/fhir/StructureDefinition/Patient)
- [HL7 FHIR immunization resource](http://hl7.org/fhir/StructureDefinition/immunization)
- [HL7 FHIR domain resource](http://hl7.org/fhir/StructureDefinition/DomainResource)
- [Government of Nepal, Ministry of Health and Population, Department of Health Services, Health Management Information System (HMIS) guideline 2075: Register, card and reporting formats](https://fwd.gov.np/cms/health‑management‑information‑system‑hmis‑guideline‑2075/)



