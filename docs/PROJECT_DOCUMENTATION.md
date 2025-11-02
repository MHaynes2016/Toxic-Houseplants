# Toxic Houseplants Project Documentation

## Project Overview
This Omeka S project documents toxic houseplants commonly found in North American homes, with a focus on providing critical safety information for pet owners and families.

## Objectives
1. Create a comprehensive database of toxic houseplants
2. Provide clear toxicity level classifications
3. Document toxic chemical compounds and their effects
4. Offer first aid guidance for pet and human exposure
5. Link to credible, authoritative sources

## Data Collection Methodology

### Source Evaluation Criteria
- Prioritize veterinary and medical professional sources
- Use established organizations (ASPCA, Pet Poison Helpline, etc.)
- Cross-reference multiple sources for accuracy
- Include scientific names for proper plant identification

### Required Information Per Plant
- **Common Name**: The name most people know the plant by
- **Scientific Name**: Botanical Latin name for accurate identification
- **Toxicity Level**: 
  - Low: Mild irritation, typically self-limiting
  - Moderate: Significant discomfort, veterinary/medical consultation recommended
  - High: Severe symptoms, emergency care required
- **Toxic Principles**: The specific chemical compounds causing toxicity
- **Affected Species**: Which animals/humans are affected
- **Symptoms**: Observable signs of poisoning
- **First Aid**: Immediate care recommendations
- **Source Links**: URLs to credible information sources

## Implementation Guide

### Setting Up Omeka S
1. Install Omeka S following official documentation
2. Install required modules:
   - CSV Import
   - Custom Vocab (optional for controlled vocabularies)
3. Import the resource template from `metadata/resource_template.json`
4. Create items using the CSV Import module with `metadata/toxic_houseplants_template.csv`

### Adding New Plants
1. Research the plant using credible sources
2. Fill in all required fields in the CSV template
3. Import via CSV Import module or manually create item
4. Upload plant images to the files/ directory (if available)
5. Link images to the appropriate item

## Credible Sources
- ASPCA Animal Poison Control Center
- Pet Poison Helpline
- National Capital Poison Center
- American Veterinary Medical Association
- University extension services
- Peer-reviewed botanical and toxicology journals

## Safety Disclaimer
This database is for educational purposes. In case of suspected poisoning:
- **Pets**: Contact ASPCA Poison Control (888-426-4435) or Pet Poison Helpline (855-764-7661)
- **Humans**: Contact Poison Control Center (1-800-222-1222) or seek emergency medical care

## Contributing
When adding plants to the database:
1. Verify information with multiple credible sources
2. Use the standardized CSV template
3. Include clear, accurate common and scientific names
4. Provide specific first aid guidance
5. Link to authoritative sources

## License
Content should be properly attributed. Plant images require permission or should be public domain/Creative Commons licensed.
