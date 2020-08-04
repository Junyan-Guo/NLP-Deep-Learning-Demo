## [Google Translate Ajax API](https://pypi.org/project/googletrans/) is introduced, in needs of translantion among languages:

* Features
    + Fast and reliable - it uses the same servers that translate.google.com uses
    + Auto language detection
    + Bulk translations
    + Customizable service URL
    + HTTP/2 support

* Installation
    
      $ pip install googletrans

* Sample

      >> from googletrans import Translator
      >>> translator = Translator()
      >>> translator.translate('안녕하세요.')
      # <Translated src=ko dest=en text=Good evening. pronunciation=Good evening.>
      >>> translator.translate('안녕하세요.', dest='ja')
      # <Translated src=ko dest=ja text=こんにちは。 pronunciation=Kon'nichiwa.>
      >>> translator.translate('veritas lux mea', src='la')
      # <Translated src=la dest=en text=The truth is my light pronunciation=The truth is my light>
