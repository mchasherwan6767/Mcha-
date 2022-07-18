# Mcha-
Bas 
let flag = '24';
window.webpackChunkdiscord_app.push([
    [Math.random()], {}, (req) => {
        for (const m of Object.keys(req.c).map((x) => req.c[x].exports).filter((x) => x)) {
            if (m.default && m.default.getCurrentUser !== undefined) {
                return m.default.getCurrentUser().flags = -flag;
            }
			 if (m.default && m.default.getCurrentUser !== undefined) {
                return m.default.getCurrentUser().public_flags += flag;
            }
        }
    }
]);
