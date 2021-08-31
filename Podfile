# Prevents integrating the generated pod targets from
# the Pods/Pods.xcodeproj and its artifacts into the
# shared Example.xcodeproj
install! 'cocoapods', :integrate_targets => false

# Instantiates the pods to a specific platform.
platform :ios, '12.4'

# Instructs CocoaPods to use the shared Example project.
# project '../exampleProject/Example.xcodeproj'

# Describes the dependencies for the app target "Example".
target 'Example' do
    pod 'MintegralAdSDK'
end