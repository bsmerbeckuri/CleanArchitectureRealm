# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'


def rx_swift
	pod 'RxSwift'
end

def rx_cocoa
	pod 'RxCocoa'
end


target 'CleanArchitectureRealm' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!
	rx_cocoa
	rx_swift

  # Pods for CleanArchitectureRealm

end

target 'Domain' do 
	use_frameworks!
	rx_swift

end

target 'RealmPlatform' do 
	use_frameworks!
	rx_swift
	pod 'RxRealm'
	pod 'RealmSwift'
	pod 'Realm'
end

