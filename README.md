# Abdullah
Landig page

Landing Page Ben Altahona Arabic Coffee Shop
· typescript
export default function BenAltahonaLandingPage() {
  return (
    <div className="min-h-screen bg-[#f8f3eb] text-[#3b2a1a] font-sans">
      {/* Hero Section */}
      <section className="relative overflow-hidden bg-gradient-to-br from-[#4b2e1f] to-[#7b4b2a] text-white">
        <div className="absolute inset-0 opacity-10 bg-[url('https://images.unsplash.com/photo-1495474472287-4d71bcdd2085?q=80&w=1600&auto=format&fit=crop')] bg-cover bg-center"></div>


        <div className="relative max-w-7xl mx-auto px-6 py-24 grid md:grid-cols-2 gap-12 items-center">
          <div>
            <h1 className="text-5xl md:text-7xl font-extrabold leading-tight mb-6">
              بن الطاحونة
            </h1>
            <p className="text-lg md:text-2xl text-[#f3e7d3] mb-8 leading-relaxed">
              أفضل أنواع البن الطازج والمحمص بعناية عشان تبدأ يومك بأقوى مزاج.
            </p>


            <div className="flex flex-wrap gap-4">
              <button className="bg-[#f0c27b] hover:bg-[#e7b566] text-[#3b2a1a] px-8 py-4 rounded-2xl text-lg font-bold shadow-xl transition-all duration-300 hover:scale-105">
                اطلب الآن
              </button>


              <button className="border border-white/40 hover:bg-white/10 px-8 py-4 rounded-2xl text-lg font-semibold transition-all duration-300">
                اعرف أكتر
              </button>
            </div>
          </div>


          <div className="flex justify-center">
            <img
              src="https://images.unsplash.com/photo-1509042239860-f550ce710b93?q=80&w=1200&auto=format&fit=crop"
              alt="Coffee"
              className="rounded-[32px] shadow-2xl w-full max-w-lg object-cover border-4 border-white/10"
            />
          </div>
        </div>
      </section>


      {/* Features */}
      <section className="max-w-7xl mx-auto px-6 py-20">
        <div className="text-center mb-14">
          <h2 className="text-4xl font-bold mb-4">ليه تختار بن الطاحونة؟</h2>
          <p className="text-lg text-[#6f5a47]">
            جودة، طعم فاخر، وتحميص يوصلك بأفضل نكهة ممكنة.
          </p>
        </div>


        <div className="grid md:grid-cols-3 gap-8">
          <div className="bg-white rounded-3xl p-8 shadow-lg hover:shadow-2xl transition-all duration-300">
            <div className="text-5xl mb-4">☕</div>
            <h3 className="text-2xl font-bold mb-3">بن فاخر</h3>
            <p className="text-[#6f5a47] leading-relaxed">
              أجود أنواع البن العربي والبرازيلي بطعم غني ومميز.
            </p>
          </div>


          <div className="bg-white rounded-3xl p-8 shadow-lg hover:shadow-2xl transition-all duration-300">
            <div className="text-5xl mb-4">🔥</div>
            <h3 className="text-2xl font-bold mb-3">تحميص طازج</h3>
            <p className="text-[#6f5a47] leading-relaxed">
              بن متحمص يوميًا للحفاظ على أقوى نكهة ورائحة.
            </p>
          </div>


          <div className="bg-white rounded-3xl p-8 shadow-lg hover:shadow-2xl transition-all duration-300">
            <div className="text-5xl mb-4">🚚</div>
            <h3 className="text-2xl font-bold mb-3">توصيل سريع</h3>
            <p className="text-[#6f5a47] leading-relaxed">
              اطلب قهوتك وهتوصلك بسرعة لحد باب البيت.
            </p>
          </div>
        </div>
      </section>


      {/* Products */}
