# image-caption-ai-challenger2017
For single model (InceptionV4 + Luong attention) it can achive cider 1.5 without finetune image model and 1.78 after finetune, using label smoothing it can improve to 1.81.    
If using nasnet cant got cider 1.75 before finetune and 1.80 after finetune. Notice nasnet might be slow if using 1 gpu, you'd better set 2 gpu with each gpu batch size 8 for gtx1080ti or each gpu batch size 16 for p40.  
Support scst reinforcement learning but not improve you can help to contribute.  
