For issues with "blind" Gemma4 models, these files increase vision tokens (image resolution processed) to 560 and include the updated Gemma4 template and tokenizer files to assist tool calling.  For safetensors with oMLX or other inference server that doesn't support the kargs to adjust vision.

Just backup your original files in the model folders and replace with these.
