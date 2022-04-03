# Speech-to-Text-converter
Amazon Transcribe analyzes audio files that contain speech and uses advanced machine learning techniques to transcribe the voice data into text.

File 1:- AudioMediaFile
python -m pip install amazon-transcribe aiofile
pip install sounddevice
It has pre-recorded audio file. It ingests audio input directly from that file and converts into text form using machine learning techniques.

File 2:- VoiceLive
import boto3
It recognizes voice of the user while he speaks . No pre-recorded audio library required.

<!-- Create a s3 bucket and copy the uri path location
 -->
