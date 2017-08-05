
KAROO_JSSIP_INSTALL=${DESTDIR}@OSS_KAROO_BRIDGE_VARLIB@

all:
	cd ${srcdir} && npm install && gulp prod
	@echo "JSSIP bound to be installed in ${KAROO_JSSIP_INSTALL}/www/jssip/"
	
install:
	rm -rf ${KAROO_JSSIP_INSTALL}/www/jssip
	mkdir -p ${KAROO_JSSIP_INSTALL}/www/jssip
	cp -rpP ${srcdir}/out/* ${KAROO_JSSIP_INSTALL}/www/jssip/
	
	
