# stegosaurus
Fast Image Steganography with numpy - encode a message into a file.

Performance is key with this library - numpy allows this library to run at near C speed while doing vector calculations, which is 95% of encoding an image.

Steps taken
- Load file (carrier)
- Load message (payload) - from file, text or binary.
- Optionally encrypt message (encrypted payload)
- Encode message into file (package)



Steganography is a very interesting topic, that is actually used quite a lot

[Add more examples here]
- Your printers encodes a secret message with yellow dots that law enforcement can use to identify
- Your smart phone screenshots have hidden patterns to identify the owner (unproven but likely)
- Digital watermarks use steganography to encode code into a image to copyright violations
- Whistle blowers use steganography to get company data out of the company.
- Nerds use steganography as a trendy way to chat with friends

https://en.wikipedia.org/wiki/Steganography


## List of companies/services where a Stegosaurus encoded files (Stegosaurus package) can be uploaded with the data remaining intact.
[Update list]


A Stegosaurus message can also be read by a screenshot of the image, this make a useful tool to digitally watermark images.

[watermark reader in process]



## Benchmark


## Usage
