1. Prepare the user/test data
2. Build the vocabulary (designating output directory)
3. Run the trained model

python Requirements/process_requirements.py (or other script)
cd SemanticRelatednessModel
python scripts/build_vocab.py user
th runModel.lua
