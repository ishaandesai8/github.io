# github.io
Charity: Water
import { Link } from "@tanstack/react-router";

[export default function CharityWaterLandingPage() {
  return (
    <main className="min-h-screen bg-[#003366] text-white">
      {/* Hero Section */}
      <section className="relative overflow-hidden px-6 py-10 md:px-16 md:py-16">
        <div className="mx-auto grid max-w-7xl items-center gap-10 md:grid-cols-2">
          <div>
            <div className="mb-4 inline-flex items-center rounded-full bg-[#FFC907] px-4 py-2 text-sm font-bold text-black">
              charity: water
            </div>

            <h1 className="text-4xl font-extrabold leading-tight text-[#FFC907] md:text-6xl">
              Create a World with Clean Water
            </h1>

            <p className="mt-5 max-w-xl text-lg leading-8 text-white/90">
              College students have the power to turn passion into real impact.
              Together, we can help bring clean and safe drinking water to
              communities around the world.
            </p>

            <div className="mt-8 flex flex-wrap gap-4">
              <a
                href="#take-action"
                className="rounded-lg bg-[#FFC907] px-6 py-3 font-bold text-black transition hover:bg-yellow-300"
              >
                Take Action
              </a>

              <a
                href="#learn-more"
                className="rounded-lg border border-white px-6 py-3 font-bold text-white transition hover:bg-white hover:text-[#003366]"
              >
                Learn More
              </a>
            </div>
          </div>

          <div className="rounded-3xl bg-white/10 p-4 shadow-2xl">
            <img
              src="https://images.unsplash.com/photo-1541919329513-35f7af297129?auto=format&fit=crop&w=900&q=80"
              alt="Child enjoying clean water"
              className="h-[360px] w-full rounded-2xl object-cover"
            />
          </div>
        </div>
      </section>

      {/* Problem Section */}
      <section id="learn-more" className="bg-white px-6 py-14 text-[#1f2933] md:px-16">
        <div className="mx-auto max-w-6xl">
          <p className="text-sm font-bold uppercase tracking-widest text-[#003366]">
            The Water Crisis
          </p>

          <h2 className="mt-3 text-3xl font-extrabold md:text-4xl">
            Millions of people still live without clean water.
          </h2>

          <p className="mt-5 max-w-3xl text-lg leading-8 text-gray-700">
            Families and communities are forced to drink unsafe water, which
            affects health, education, and daily life. This campaign helps
            students understand the issue while showing simple ways they can
            make a real difference.
          </p>

          <div className="mt-10 grid gap-6 md:grid-cols-3">
            <div className="rounded-2xl bg-[#003366] p-6 text-white">
              <h3 className="text-4xl font-extrabold text-[#FFC907]">703M</h3>
              <p className="mt-3 font-semibold">People without clean water</p>
            </div>

            <div className="rounded-2xl bg-[#FFC907] p-6 text-black">
              <h3 className="text-4xl font-extrabold">$40</h3>
              <p className="mt-3 font-semibold">
                Can help one person access clean water
              </p>
            </div>

            <div className="rounded-2xl bg-gray-100 p-6 text-[#1f2933]">
              <h3 className="text-4xl font-extrabold text-[#003366]">100%</h3>
              <p className="mt-3 font-semibold">
                Public donations fund clean water projects
              </p>
            </div>
          </div>
        </div>
      </section>

      {/* Campus Action Section */}
      <section id="take-action" className="px-6 py-16 md:px-16">
        <div className="mx-auto max-w-6xl text-center">
          <p className="text-sm font-bold uppercase tracking-widest text-[#FFC907]">
            How Your Campus Can Help
          </p>

          <h2 className="mt-3 text-3xl font-extrabold md:text-4xl">
            Small student actions can create lasting change.
          </h2>

          <p className="mx-auto mt-5 max-w-3xl text-lg leading-8 text-white/85">
            Whether you donate, start a campus fundraiser, or share the message
            with friends, you can help bring attention to the global water
            crisis and support communities in need.
          </p>

          <div className="mt-10 grid gap-6 md:grid-cols-3">
            <div className="rounded-2xl bg-white p-6 text-left text-[#1f2933]">
              <h3 className="text-xl font-extrabold">Donate</h3>
              <p className="mt-3 text-gray-700">
                Give what you can and help fund clean water access for people
                around the world.
              </p>
            </div>

            <div className="rounded-2xl bg-white p-6 text-left text-[#1f2933]">
              <h3 className="text-xl font-extrabold">Start a Campaign</h3>
              <p className="mt-3 text-gray-700">
                Create a campus fundraiser with your friends, club, dorm, or
                student organization.
              </p>
            </div>

            <div className="rounded-2xl bg-white p-6 text-left text-[#1f2933]">
              <h3 className="text-xl font-extrabold">Spread the Word</h3>
              <p className="mt-3 text-gray-700">
                Share the mission online and help more students learn about the
                clean water crisis.
              </p>
            </div>
          </div>

          <div className="mt-10">
            <a
              href="https://www.charitywater.org/"
              target="_blank"
              rel="noreferrer"
              className="inline-block rounded-lg bg-[#FFC907] px-8 py-4 text-lg font-extrabold text-black transition hover:bg-yellow-300"
            >
              Join the Movement
            </a>
          </div>
        </div>
      </section>

      {/* Footer */}
      <footer className="border-t border-white/20 px-6 py-6 text-center text-sm text-white/70">
        Built for college students inspired to take action on the global water crisis.
      </footer>
    </main>
  );
](https://ishaandesai8.github.io/charitywater/)
