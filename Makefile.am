
KAROO_JSSIP_INSTALL=${DESTDIR}@OSS_KAROO_BRIDGE_VARLIB@

all:
	cd ${srcdir} && npm install && rm -rf out && gulp prod
	@echo "JSSIP bound to be installed in ${KAROO_JSSIP_INSTALL}/www/webrtc/"
	
install: all
	rm -rf ${KAROO_JSSIP_INSTALL}/www/webrtc
	mkdir -p ${KAROO_JSSIP_INSTALL}/www/webrtc
	cp -rpP ${srcdir}/out/* ${KAROO_JSSIP_INSTALL}/www/webrtc/
	
	
