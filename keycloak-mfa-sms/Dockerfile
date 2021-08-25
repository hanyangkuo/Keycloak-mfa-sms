FROM docker.io/jboss/keycloak:14.0.0
COPY standalone/deployments/keycloak-metrics-spi-2.4.0.jar /opt/jboss/keycloak/standalone/deployments
COPY standalone/deployments/keycloak-metrics-spi-2.4.0.jar.dodeploy /opt/jboss/keycloak/standalone/deployments
COPY standalone/deployments/dasniko-keycloak-2fa-sms-authenticator-1.0-SNAPSHOT.jar /opt/jboss/keycloak/standalone/deployments
COPY standalone/deployments/dasniko-keycloak-2fa-sms-authenticator-1.0-SNAPSHOT.jar.dodeploy /opt/jboss/keycloak/standalone/deployments
COPY theme-resources/templates/login-sms.ftl /opt/jboss/keycloak/themes/base/login

ENV AWS_ACCESS_KEY_ID=AKIASIU2QXJDUF5I54HO
ENV AWS_SECRET_ACCESS_KEY=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