EXTRA_CFLAGS += -fno-pic
obj-$(CONFIG_CRYPTO_DEV_QCEDEV) += qcedev.o
ifeq ($(CONFIG_CRYPTO_DEV_QCE40), y)
	obj-$(CONFIG_CRYPTO_DEV_QCE) += qce40.o
else
	obj-$(CONFIG_CRYPTO_DEV_QCE) += qce.o
endif
obj-$(CONFIG_CRYPTO_DEV_QCRYPTO) += qcrypto.o
obj-$(CONFIG_CRYPTO_DEV_OTA_CRYPTO) += ota_crypto.o
