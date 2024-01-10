# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'BodyMeasurment' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for BodyMeasurment

end

target 'BodyMeasurmentObjC' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for BodyMeasurmentObjC
pod 'GoogleMLKit/BarcodeScanning', '4.0.0'
pod 'GoogleMLKit/FaceDetection', '4.0.0'
pod 'GoogleMLKit/ImageLabeling', '4.0.0'
pod 'GoogleMLKit/ImageLabelingCustom', '4.0.0'
pod 'GoogleMLKit/ObjectDetection', '4.0.0'
pod 'GoogleMLKit/ObjectDetectionCustom', '4.0.0'
pod 'GoogleMLKit/PoseDetection', '4.0.0'
pod 'GoogleMLKit/PoseDetectionAccurate', '4.0.0'
pod 'GoogleMLKit/SegmentationSelfie', '4.0.0'
pod 'GoogleMLKit/TextRecognition', '4.0.0'
pod 'GoogleMLKit/TextRecognitionChinese', '4.0.0'
pod 'GoogleMLKit/TextRecognitionDevanagari', '4.0.0'
pod 'GoogleMLKit/TextRecognitionJapanese', '4.0.0'
pod 'GoogleMLKit/TextRecognitionKorean', '4.0.0'


post_install do |installer|
  installer.generated_projects.each do |project|
    project.targets.each do |target|
        target.build_configurations.each do |config|
            config.build_settings['CODE_SIGNING_ALLOWED'] = 'NO'
         end
    end
  end
end

end
