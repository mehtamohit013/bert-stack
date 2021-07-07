# bert-android_stack
Notebooks, results and dataset on android dataset

## Baseline
Contains all the baseline notebook with the saved output trained on android dataset and their traces (Model loss, accuracy on train) (related+linked)

Note : Evaluator Section of the code in the notebooks contains some bug and are fork of sentence-transformer evaluators

1. BERT_Only.ipynb  - Unimodal
		BERT Bi-encoder, passing title+tag+body as an input
2. BERT_Only+Tags - Unimodal
	(BERT + BiLSTM) Bi-encoder,passing title+body to the bert and tag into BiLSTM
3. BERT_BERT.ipynb - Unimodal
	(BERT+BERT) Bi-encoder, passing title+body to one BERT and tags to another BERT
4. RESNET+BERT - multimodal 
	Resnet + BERT, passing title+tag+body as an input to BERT and images to RESNET and concat both
5.	Image Pairs Related.docx
	Contains stats about number of images and non images pair in train,dev and test 

## MultiModal
1. Multimodal_final.ipynb
	Final multimodal notebook consists of model implemented in Xinyu paper, with optimized dataset spilliting and exclusivity in dev,test and train
2. Multimodal_1.ipynb
	Multimodal notebook with simple dataset splitting
	
## Drive
1. all_data_softmax_3epoch_model
	contains saved sentence-transformer model (using sbert lib) trained on combining all the datasets available (related only)
2. Linked_android_model(cross_encoder)
	Contains the result of training an cross encoder (sentence transformer) on linked dataset
3. Linked 
	Contains all the baseline evaluated on linked dataset seperately
	
