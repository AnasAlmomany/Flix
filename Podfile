platform :ios, '8.0'

use_frameworks!
inhibit_all_warnings!

def source
  pod 'RxSwift', '~> 4.0'
  pod 'RxCocoa', '~> 4.0'
  pod 'RxDataSources', '~> 3.0'
end

target 'Flix' do
  source
  target 'FlixTests' do
      inherit! :search_paths
  end
end

target 'Example' do
  source
  pod 'RxKeyboard', '~> 0.7'
end
