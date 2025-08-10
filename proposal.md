# NHS Digital Therapy Assistant — Proposal

## Background
Occupational therapy services within the NHS are facing increased demand, limited staffing, and growing waiting lists. Delays in assessment can worsen patient outcomes.

## Vision
An open-source AI-powered digital therapy assistant that:
- Collects structured patient information before appointments
- Flags high-priority cases for faster intervention
- Guides patients with exercises or resources while they wait

## Technical Approach
1. **Conversational Interface**
   - Powered by fine-tuned LLaMA or Mistral LLM
   - Trained with validated NHS OT assessment questionnaires
   - Supports multi-language input/output

2. **Deployment**
   - On-device for privacy, or on NHS-secure servers
   - Offline mode for community clinics

3. **Integration**
   - NHS service directories
   - Electronic health records (FHIR-compliant)
   - Referral management systems

4. **Safety & Governance**
   - Rule-based filters to avoid unsafe advice
   - Clinician oversight for continuous improvement

## Expected Outcomes
- Faster, fairer access to occupational therapy
- Data-driven triage decisions
- Increased patient satisfaction
