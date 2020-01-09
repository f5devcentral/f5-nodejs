f5-nodesjs module
-----------------
F5 provides an API for using Node.js with the f5-nodejs module located in the node_modules folder in each extension folder. The nodejs library for iRules LX is NOT published to NPM (https://www.npmjs.com), and only resides on the F5 BIG-IP system.

Using Node.js outside of this API may lead to major performance degradations, such as binding ports on the management plane with the net.Server module.

Important: F5 does not provide support for iRules LX Node.js outside of the F5-provided API.

You can find the support policy for the F5 nodejs library and iRules LX properties and limitations at https://support.f5.com/csp/article/K16221101.


The f5-nodejs files on the BIG-IP system are in the following locations:
- /usr/share/packages/nodejs/f5-nodejs-0.12.tgz
- /usr/share/packages/nodejs/f5-nodejs.tgz
- /usr/share/packages/nodejs/f5-nodejs-6.tgz


Updated: 1/8/2020