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
	

