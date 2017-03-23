# Preprocess data sets

  ./preprocess.sh

# Configurations

   Edit the file: config.py
  
# Training

  ./train.sh

# Decoding

  ./translate.sh

# Postprocess the translation output

  ./postprocess-test.sh < data/IWSLT15.TED.tst2015.en-vi.truecase.hyp.vi > data/IWSLT15.TED.tst2015.en-vi.truecase.hyp.vi.postprocessed
