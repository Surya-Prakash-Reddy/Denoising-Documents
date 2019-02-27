<h1>Denoising Documents</h1>

<h2>About Project:</h2>
<p>
  The goal of this project is to remove unnecessary noise from the documents making them easy to read as well as easy for Optical 
  Character Recognition(OCR) to scan the documents and convert them into digital format so that one could use it anytime and anywhere.
  <br />
  <img src="https://github.com/SurajChinna/Denoising-Documents/blob/master/assets/img1.png" />
  In the image we can see that the first document has background noise the second document is a cleaned document after cleaning 
  the first document. Apart from just background noise there can be other types of noise such as coffee stains or folds
  <br />
  I have used denoising autoencoders to clean the documents. The autoencoders are coded using Convolutional Neural Networks(CNNs). An 
  autoencoder has two parts, one <b>encoder</b> and other <b>decoder</b>. The encoder encodes the data and decoder decodes the encoded 
  part. After passing the image through the CNNs, in the initial layers style is detected whereas in deeper layers content in image is 
  detected. Hence, after passing the image into more than two convolutional layers, we are remained with just the content but with a 
  different shape which is encoded and that is not understandable directly. We next pass this encoded part through <b>decoder</b> which 
  decodes and generate final image without noise. 
</p>

<h2>Languages or frameworks used</h2>
<p>
<ul>
  <li>Python: language</li>
 <li>PyTorch: open source deep learning framework</li>
 <li>PIL: python library to open, manipulate and save images</li>
 <li>Matplotlib: python library to draw and visualise graphs and images</li>
</ul>
</p>
