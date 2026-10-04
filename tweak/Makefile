TARGET := iphone:clang:latest:14.0
ARCHS := arm64 arm64e
THEOS_PACKAGE_SCHEME := roothide

INSTALL_TARGET_PROCESSES = UberEats

include $(THEOS)/makefiles/common.mk

TWEAK_NAME = UberFresh
UberFresh_FILES = Tweak.x
UberFresh_CFLAGS = -fobjc-arc
UberFresh_FRAMEWORKS = UIKit Foundation CoreLocation AdSupport SystemConfiguration
UberFresh_FILTER_FILES = UberFresh.plist

include $(THEOS_MAKE_PATH)/tweak.mk