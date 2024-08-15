# Late Fusion Models in Multimodal ML

## What is Late Fusion?

Late Fusion involves training separate models for each modality and combining their outputs at the final decision stage. This approach leverages the strengths of individual models.

## Advantages

- **Modality Independence**: Each modality can be processed independently, allowing specialized models.
- **Flexibility**: Easier to integrate additional modalities without retraining the entire system.

## Disadvantages

- **Higher Complexity**: Requires managing multiple models.
- **Limited Interaction**: Reduced capacity for learning interactions between modalities.

## Implementation Example

- **Step 1**: Train a separate model for each modality.
- **Step 2**: Combine the outputs (e.g., via averaging, voting, or a meta-learner).
- **Step 3**: Make the final decision based on the combined outputs.
