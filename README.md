# TransUNet
TrabsUNet Segmentation implementation for ICH


## Dependencies
- Python 3.9
- `pip install -r requirements.txt`

## Training
- Training process can be started with following command.
    - `python main.py --mode train --model_path /workspaces/TransUNet/model --train_path /workspaces/TransUNet/data/train --test_path /workspaces/TransUNet/data/train`

## Inference
- After model is trained, inference can be run with following command.
    - `python main.py --mode inference --model_path ./path/to/model --image_path ./path/to/image`
    
## Other Implementations
- [Self Attention CV / The AI Summer](https://github.com/The-AI-Summer/self-attention-cv)
- [SOTA Vision / 04RR](https://github.com/04RR/SOTA-Vision)

## References
- [1] [TransUNet: Transformers Make Strong Encoders for Medical Image Segmentation](https://arxiv.org/abs/2102.04306)
