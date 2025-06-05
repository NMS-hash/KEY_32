const fastify = require("fastify")({ logger: true });
const path = require("path");

// تسجيل ملفات الستاتيك (مثل CSS أو صور)
fastify.register(require("@fastify/static"), {
  root: path.join(__dirname, "public"),
  prefix: "/",
});

// تسجيل محرك القوالب (Handlebars هنا)
fastify.register(require("@fastify/view"), {
  engine: {
    handlebars: require("handlebars"),
  },
});

// صفحة رئيسية تعرض "مرحباً في موقعي!"
fastify.get("/", async (request, reply) => {
  return reply.view("/src/index.html", { message: "مرحباً في موقعي على Render!" });
});

// بدء السيرفر على المنفذ المحدد (PORT من البيئة أو 3000)
const PORT = process.env.PORT || 3000;
fastify.listen({ port: PORT, host: "0.0.0.0" }, (err, address) => {
  if (err) {
    fastify.log.error(err);
    process.exit(1);
  }
  fastify.log.info(`Server listening on ${address}`);
});
