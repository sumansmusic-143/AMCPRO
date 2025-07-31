# AMCPRO
import React from "react";

export default function AMCPROLandingPage() {
  return (
    <div className="min-h-screen bg-gradient-to-br from-gray-900 to-black text-white font-sans">
      {/* Header */}
      <header className="flex items-center justify-between px-6 py-4 border-b border-gray-700">
        <h1 className="text-2xl font-bold text-blue-400">AMCPRO</h1>
        <div className="space-x-4">
          <button className="px-4 py-2 bg-blue-600 rounded hover:bg-blue-700">Login</button>
          <button className="px-4 py-2 bg-green-600 rounded hover:bg-green-700">Register</button>
        </div>
      </header>

      {/* Hero Section */}
      <section className="flex flex-col items-center justify-center text-center py-20 px-6">
        <h2 className="text-4xl font-extrabold mb-4">Earn Coins for Every Action You Take</h2>
        <p className="text-lg text-gray-300 max-w-2xl">
          Watch YouTube videos, Like & Comment on Instagram, Install Apps, Write Reviews, and Earn Real Rewards with AMCPRO.
        </p>
        <button className="mt-8 px-6 py-3 bg-yellow-500 text-black font-semibold rounded hover:bg-yellow-600">
          Get Started Now
        </button>
      </section>

      {/* Features */}
      <section className="py-16 px-6 bg-gray-800">
        <h3 className="text-3xl font-bold text-center mb-12">How It Works</h3>
        <div className="grid grid-cols-1 md:grid-cols-3 gap-8 max-w-6xl mx-auto">
          {[
            { title: "Watch & Earn", desc: "Watch YouTube videos & get rewarded instantly." },
            { title: "Like + Comment", desc: "Engage on Instagram or YouTube & earn coins." },
            { title: "App Installs", desc: "Install apps and earn more coins per task." },
            { title: "Google Reviews", desc: "Leave real reviews and gain high coin value." },
            { title: "Daily Tasks", desc: "Complete new tasks every day for rewards." },
            { title: "Withdraw Anytime", desc: "Convert coins to Paytm, UPI, or Recharge." }
          ].map((item, i) => (
            <div key={i} className="bg-gray-900 p-6 rounded-xl shadow-lg hover:scale-105 transition">
              <h4 className="text-xl font-semibold mb-2 text-blue-300">{item.title}</h4>
              <p className="text-gray-400">{item.desc}</p>
            </div>
          ))}
        </div>
      </section>

      {/* Footer */}
      <footer className="text-center py-8 border-t border-gray-700 text-gray-500 text-sm">
        © {new Date().getFullYear()} AMCPRO. All rights reserved.
      </footer>
    </div>
  );
}
