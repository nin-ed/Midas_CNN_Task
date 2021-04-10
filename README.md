# Midas_CNN_Task
Pretrained model is available from here - https://drive.google.com/file/d/1Q81L4bxmLKTpazxexOQgD_ly3dZUnSZl/view?usp=sharing

Trained model of randomly initialized network from part 2 - https://drive.google.com/file/d/1ZEioNeuCOmkWtWn0y924sZfdQr692Euc/view?usp=sharing



Save this and, 
1. import class Model
2. Initialize as **model = Model(input_channel, number_of_labels)** 
3. Now run, **model.load_state_dict(torch.load(path))**, where 'path' is the location where you have stored the above downloaded model.
4. Now use the model. If it gives error, simply run, **model = model.cuda()**
