# wash-works-business
small business
export default function WashWorksWebsite() {
  return (
    <div className="min-h-screen bg-gray-950 text-white font-sans">
      {/* Hero Section */}
      <section className="relative px-6 py-24 text-center bg-gradient-to-b from-black to-gray-900">
        <div className="max-w-4xl mx-auto">
          <h1 className="text-5xl md:text-7xl font-bold tracking-tight">
            WashWorks
          </h1>
          <p className="mt-6 text-lg md:text-xl text-gray-300">
            Professional Power Washing Services
          </p>
          <p className="mt-4 text-gray-400 max-w-2xl mx-auto">
            We help homes, driveways, patios, and businesses look brand new with clean, reliable, and affordable pressure washing.
          </p>

          <div className="mt-8 flex justify-center gap-4 flex-wrap">
            <button className="bg-white text-black px-6 py-3 rounded-2xl font-semibold shadow-lg hover:scale-105 transition">
              Get a Free Quote
            </button>
            <button className="border border-gray-600 px-6 py-3 rounded-2xl hover:bg-gray-800 transition">
              View Services
            </button>
          </div>
        </div>
      </section>

      {/* Services */}
      <section className="px-6 py-20 bg-gray-900">
        <div className="max-w-6xl mx-auto">
          <h2 className="text-4xl font-bold text-center mb-12">Our Services</h2>

          <div className="grid md:grid-cols-3 gap-8">
            <div className="bg-gray-800 p-8 rounded-3xl shadow-xl">
              <h3 className="text-2xl font-semibold mb-4">Driveway Cleaning</h3>
              <p className="text-gray-400">
                Remove dirt, stains, and buildup to restore your driveway’s clean appearance.
              </p>
            </div>

            <div className="bg-gray-800 p-8 rounded-3xl shadow-xl">
              <h3 className="text-2xl font-semibold mb-4">House Washing</h3>
              <p className="text-gray-400">
                Safe and effective exterior cleaning for siding, brick, and more.
              </p>
            </div>

            <div className="bg-gray-800 p-8 rounded-3xl shadow-xl">
              <h3 className="text-2xl font-semibold mb-4">Patio & Deck Cleaning</h3>
              <p className="text-gray-400">
                Refresh outdoor spaces and make them look like new again.
              </p>
            </div>
          </div>
        </div>
      </section>

      {/* About */}
      <section className="px-6 py-20 bg-black">
        <div className="max-w-4xl mx-auto text-center">
          <h2 className="text-4xl font-bold mb-6">Why Choose WashWorks?</h2>
          <p className="text-gray-400 text-lg leading-relaxed">
            At WashWorks, we focus on quality work, honest pricing, and customer satisfaction. Whether you need your driveway cleaned or your whole home refreshed, we’re here to help your property shine.
          </p>
        </div>
      </section>

      {/* Contact */}
      <section className="px-6 py-20 bg-gray-900">
        <div className="max-w-3xl mx-auto text-center">
          <h2 className="text-4xl font-bold mb-6">Contact Us</h2>
          <p className="text-gray-400 mb-8">
            Ready to make your property look brand new? Reach out today for a free estimate.
          </p>

          <div className="bg-gray-800 rounded-3xl p-8 shadow-xl space-y-4">
            <p className="text-lg">📞 (901) 706-5777</p>
            <p className="text-lg">✉️ washworks@email.com</p>
            <p className="text-lg">📍 Lakeland, Tennessee</p>
          </div>
        </div>
      </section>

      {/* Footer */}
      <footer className="bg-black py-6 text-center text-gray-500 text-sm">
        © 2026 WashWorks. All rights reserved.
      </footer>
    </div>
  )
}
