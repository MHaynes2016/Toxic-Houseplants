# Metadata Quick Reference Guide

## CSV Import Instructions

### Preparing Your Data
1. Use the template at `metadata/toxic_houseplants_template.csv`
2. Fill in all required columns:
   - Common Name (required)
   - Scientific Name (required)
   - Toxicity Level (required: low/moderate/high)
   - Toxic Principles (required)
   - Affected Species (required)
   - Symptoms (required)
   - First Aid (required)
   - Source Links (required)

### Importing into Omeka S
1. Navigate to Omeka S admin panel
2. Go to Modules → CSV Import
3. Upload your completed CSV file
4. Map CSV columns to Omeka S properties:
   - Common Name → dcterms:title
   - Scientific Name → dcterms:alternative
   - Toxicity Level → dcterms:extent
   - Toxic Principles → dcterms:subject
   - Affected Species → dcterms:coverage
   - Symptoms → dcterms:abstract
   - First Aid → dcterms:bibliographicCitation
   - Source Links → dcterms:source
5. Select the "Toxic Houseplant" resource template
6. Complete the import

## Resource Template Fields

### Dublin Core Terms Mapping
- **dcterms:title** - Common Name
- **dcterms:alternative** - Scientific Name
- **dcterms:description** - General description (optional)
- **dcterms:extent** - Toxicity Level
- **dcterms:subject** - Toxic Principles
- **dcterms:coverage** - Affected Species
- **dcterms:abstract** - Symptoms
- **dcterms:bibliographicCitation** - First Aid
- **dcterms:source** - Source Links

## Controlled Vocabularies

### Toxicity Levels
- **Low**: Mild symptoms, typically self-limiting
- **Moderate**: Requires monitoring, may need professional care
- **High**: Requires immediate emergency care

### Common Toxic Principles
- Calcium oxalate crystals
- Cardiac glycosides
- Cycasin
- Triterpenoid saponins
- Lycorine
- Soluble oxalates
- Insoluble oxalates

### Affected Species
- Cats
- Dogs
- Humans
- (Can list combinations, e.g., "Cats, Dogs, Humans")

## Best Practices
1. Always use the scientific name for accurate identification
2. Multiple common names can be added in description field
3. Be specific about symptoms (e.g., "oral irritation, excessive drooling")
4. First aid should be concise but actionable
5. Include reputable source URLs (ASPCA, veterinary organizations)
6. Use consistent formatting for multi-value fields
