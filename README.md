cat > README.md << 'EOF'
# Route Resilience ISRO

Occlusion-robust road extraction from satellite imagery with graph-theoretic criticality analysis for urban mobility resilience.

## Pipeline

Satellite Image → Road Segmentation → Skeletonization → Graph Healing → Criticality Analysis → Stress Simulation → Dashboard

## Team Modules

- DL / PyTorch: segmentation model, losses, training, inference
- Algorithms / Math: skeletonization, graph healing, centrality, resilience index
- Backend / Data: tiling, preprocessing, file pipeline, APIs
- Frontend / Product: Streamlit dashboard, maps, demo storytelling
EOF