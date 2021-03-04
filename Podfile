platform :ios, '11.0'
inhibit_all_warnings!
#source 'https://github.com/CocoaPods/Specs.git'
#source 'https://mirrors.tuna.tsinghua.edu.cn/git/CocoaPods/Specs.git'

target 'SLModularisation' do
  use_frameworks!

#  pod 'ModuleComm', :path => 'Module/ModuleComm'
#  pod 'ModuleGuide', :path => 'Module/ModuleGuide'
#  pod 'ModuleHome', :path => 'Module/ModuleHome'
#  pod 'ModuleSecond', :path => 'Module/ModuleSecond'
#  pod 'ModuleProfile', :path => 'Module/ModuleProfile'
#  pod 'SLJGSDK', :path => 'Module/ModuleComm/SLJGSDK'
#  pod 'ModuleResource', :path => 'Module/ModuleResource'

  pod 'ModuleComm', :git => 'https://github.com/2NU71AN9/SLModularisation-ModuleComm.git', :commit => 'e1fd8314e65194fbf3fa4bd66a543e655f6f7214'
  pod 'ModuleGuide', :git => 'https://github.com/2NU71AN9/SLModularisation-ModuleGuide.git', :commit => '51e6d476618721ff95835b752116bb96f6c134e8'
  pod 'ModuleHome', :git => 'https://github.com/2NU71AN9/SLModularisation-ModuleHome.git', :commit => 'd4613a2ad1fa313ca244210bd17c6ebca7d5d0ef'
  pod 'ModuleSecond', :git => 'https://github.com/2NU71AN9/SLModularisation-ModuleSecond.git', :commit => '2bed0ad9fe8e3999f939bd5bf3e86837323992c1'
  pod 'ModuleProfile', :git => 'https://github.com/2NU71AN9/SLModularisation-ModuleProfile.git', :commit => '93c5af5b379a84d8a1c2e6b87632b48faeab8152'
  pod 'ModuleResource', :git => 'https://github.com/2NU71AN9/SLModularisation-ModuleResource.git'
  pod 'SLJGSDK', :git => 'https://gitee.com/XsTlX/sljgsdk.git'
  pod 'JXPhotoBrowser', '3.1.2'
  
  post_install do |installer|
    system 'sh mk_modulemap.sh Pods'
  end
  
end
