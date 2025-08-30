# Vadim-Landing-Page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>React Native Mastery</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;700;900&display=swap" rel="stylesheet">
    <style>
        /* CSS Reset/Normalization */
        *, *::before, *::after { box-sizing: border-box; }
        body, h1, h2, p { margin: 0; }
        html, body {
            overflow-x: hidden;
            scroll-behavior: smooth;
        }
        body {
            font-family: 'Inter', sans-serif;
            -webkit-font-smoothing: antialiased;
            -moz-osx-font-smoothing: grayscale;
            background-color: #0F172A; /* Slate 900 */
            color: #CBD5E1; /* Slate 300 */
        }
        .greased-slide > p {
            margin-bottom: 1.25rem;
            font-size: 1.125rem;
            line-height: 1.8;
        }
        @media (max-width: 768px) {
            .greased-slide > p {
                font-size: 1rem;
            }
        }
        .fascination-headline {
            font-size: 2.25rem;
            font-weight: 900;
            line-height: 1.2;
            color: #FFFFFF;
            margin-bottom: 2rem;
            text-align: center;
        }
        @media (max-width: 768px) {
            .fascination-headline {
                font-size: 1.75rem;
            }
        }
        .cta-button {
            transition: all 0.3s ease;
        }
        .cta-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
        }
        .vsl-container {
            position: relative;
            cursor: pointer;
            border-radius: 0.5rem;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0,0,0,0.5);
            border: 2px solid #334155;
        }
        .vsl-play-button {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 80px;
            height: 80px;
            background-color: rgba(0, 0, 0, 0.6);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: all 0.2s ease;
        }
        .vsl-container:hover .vsl-play-button {
            transform: translate(-50%, -50%) scale(1.1);
            background-color: rgba(225, 48, 108, 0.9);
        }
        .vsl-play-button svg {
            width: 40px;
            height: 40px;
            fill: white;
            margin-left: 5px;
        }
        .bullet-point-icon {
            min-width: 24px;
        }
    </style>
</head>
<body class="bg-slate-900 text-slate-300">

    <!-- Wrapper -->
    <div class="w-full max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">

        <!-- HERO SECTION -->
        <section class="text-center py-20 sm:py-24">
            <p class="text-sm font-bold uppercase tracking-widest text-pink-500 mb-4">FOR DEVELOPERS WITH UNFINISHED PROJECTS</p>
            <h1 class="text-4xl sm:text-5xl lg:text-6xl font-black text-white leading-tight mb-6">
                Go From Idea To A Live, Portfolio-Ready Mobile App In 90 Days… By Building 7 Real-World Clones.
            </h1>
            <p class="text-lg sm:text-xl text-slate-400 max-w-2xl mx-auto mb-8">
                …without ever getting stuck in another “how-to” tutorial loop or wasting months on a project you never launch.
            </p>
            <div class="vsl-container w-full max-w-2xl mx-auto mb-10">
                <img src="https://placehold.co/1280x720/1e293b/cbd5e1?text=Click+To+See+How" alt="Video thumbnail showing a code editor and an app preview" class="w-full h-auto block">
                <div class="vsl-play-button">
                    <svg viewBox="0 0 24 24"><path d="M8 5v14l11-7z"></path></svg>
                </div>
            </div>
            <a href="#offer" class="cta-button inline-block bg-pink-600 text-white font-bold text-lg px-10 py-4 rounded-lg shadow-lg hover:bg-pink-700">
                Start Building Real Apps
            </a>
        </section>

        <!-- PROBLEM IDENTIFICATION -->
        <section class="py-20 sm:py-24 border-t border-slate-800">
            <h2 class="fascination-headline">
                Your Hard Drive is a Graveyard of Half-Finished Apps, Isn't It?
            </h2>
            <div class="greased-slide max-w-2xl mx-auto text-left">
                <p>
                    You’re a good developer. Maybe even a great one. You know JavaScript. You get how React works.
                </p>
                <p>
                    You’ve probably followed dozens of tutorials. The Netflix clone. The social media app. The to-do list that was supposed to teach you state management.
                </p>
                <p>
                    Each one started with a spark of excitement. “This is it,” you thought. “This is the one I’ll actually finish and put in my portfolio.”
                </p>
                <p>
                    But then… life happens.
                </p>
                <p>
                    You hit a wall with the navigation. The backend integration becomes a nightmare. Or you just lose steam, staring at a screen of perfectly functional code that feels… empty. Devoid of purpose.
                </p>
                <p>
                    So it sits there. In a folder named `project-final-v2-really-final`… collecting digital dust.
                </p>
                <p>
                    And the cost of this isn't just wasted time.
                </p>
                <p>
                    It’s the quiet dread that you’re falling behind. It’s the sting of seeing other developers—maybe even ones with less experience—launching their side projects and getting the recognition you know you deserve.
                </p>
                <p>
                    It’s the fear that your great app idea will remain just that… an idea.
                </p>
                <p>
                    But what if the problem isn't your skill, or your discipline? What if the entire way you’ve been taught to learn is fundamentally broken?
                </p>
            </div>
        </section>

        <!-- ORIGIN STORY -->
        <section class="py-20 sm:py-24 border-t border-slate-800">
            <h2 class="fascination-headline">
                I Was a FAANG Engineer Who Couldn't Launch a Simple App
            </h2>
            <div class="greased-slide max-w-2xl mx-auto text-left">
                <p>
                    My name is Vadim, and for years I had what many would call a dream job. I was a software engineer at a top tech company, working on complex problems with brilliant people.
                </p>
                <p>
                    But I had a secret. A frustrating one.
                </p>
                <p>
                    When I went home, I wanted to build my own things. Little apps, side projects, startup ideas. But I’d get stuck on the simplest things. Things my job never prepared me for.
                </p>
                <p>
                    Deployment? Setting up a full, end-to-end environment? Making architectural decisions for a project that didn't have a team of 20 seniors guiding it? I was completely lost.
                </p>
                <p>
                    My "enterprise" skills felt useless for the scrappy, real-world work of an independent builder.
                </p>
                <p>
                    I saw so many courses and tutorials that promised to teach React Native. But they all did the same thing: they taught isolated skills. A lesson on components here, a lesson on hooks there.
                </p>
                <p>
                    They never taught you how to *think* like an app builder. They never showed you the messy middle part—the part where you connect the dots, overcome roadblocks, and actually PUSH TO PRODUCTION.
                </p>
                <p>
                    The breakthrough came when I stopped trying to *learn* and started trying to *ship*.
                </p>
                <p>
                    I decided to build a real-world clone of an app I used every day. Not just the front-end. Everything. The logic, the state, the navigation, the feel. The goal wasn’t to "learn a concept," it was to have a functioning app, no matter what.
                </p>
                <p>
                    It was a painful process. But by the end, I had learned more than years of tutorials had ever taught me. I finally understood the *entire* process. I had built confidence.
                </p>
                <p>
                    I realized then that conventional learning is backwards. It gives you the bricks, but never the blueprint for the building.
                </p>
            </div>
        </section>

        <!-- SOLUTION REVELATION -->
        <section class="py-20 sm:py-24 border-t border-slate-800">
            <h2 class="fascination-headline">
                The “Build-to-Launch” System That Turns Tutorials Into Tangible Assets
            </h2>
            <div class="greased-slide max-w-2xl mx-auto text-left">
                <p>
                    The only way to gain the confidence to launch apps… is to launch apps.
                </p>
                <p>
                    It sounds obvious, but almost no one teaches this way.
                </p>
                <p>
                    That’s why I created a system based on one principle: <strong class="text-white">Every single thing you build must be a complete, real-world project worthy of a portfolio.</strong>
                </p>
                <p>
                    No more isolated "lessons." No more abstract theory.
                </p>
                <p>
                    Instead, you build real applications from the ground up. You’ll build a Threads clone. A Netflix clone. An AI agent app. Seven of them.
                </p>
                <p>
                    You'll encounter the same roadblocks real developers face. And you'll learn to solve them, because the goal isn't to get a certificate—it's to get a finished product.
                </p>
                <p class="font-bold text-white mt-12 mb-6 text-2xl">Here's what this process gives you:</p>

                <div class="space-y-6">
                    <!-- Bullet -->
                    <div class="flex items-start">
                        <svg class="h-6 w-6 text-pink-500 mr-4 bullet-point-icon" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                        <div>
                            <strong class="text-white">Build a Portfolio of 7 Functional Mobile Apps…</strong> so you stop feeling like an imposter and start having undeniable proof of your skills. You become the developer who doesn’t just talk, but ships.
                        </div>
                    </div>
                    <!-- Bullet -->
                    <div class="flex items-start">
                        <svg class="h-6 w-6 text-pink-500 mr-4 bullet-point-icon" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                        <div>
                            <strong class="text-white">Master React Native & Expo from A to Z…</strong> which means you can finally take that startup idea from a napkin sketch to a live app on the App Store, all by yourself. You become a self-sufficient creator.
                        </div>
                    </div>
                    <!-- Bullet -->
                    <div class="flex items-start">
                        <svg class="h-6 w-6 text-pink-500 mr-4 bullet-point-icon" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                        <div>
                            <strong class="text-white">Learn End-to-End App Architecture and Deployment…</strong> so you feel the immense pride of seeing something YOU built being used by real people. You become a true full-stack mobile developer.
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- PRODUCT INTRODUCTION -->
        <section class="py-20 sm:py-24 border-t border-slate-800">
            <h2 class="fascination-headline">
                Introducing: React Native Mastery
            </h2>
            <div class="greased-slide max-w-2xl mx-auto text-left">
                <p>
                    React Native Mastery is the result of this "Build-to-Launch" system.
                </p>
                <p>
                    It is not another video library. It is a guided journey designed to do one thing: fill your portfolio with real, impressive mobile apps and give you the confidence to build any app you can imagine.
                </p>
                <p>
                    This is the exact opposite of the generic courses you’ve tried.
                </p>
                <p>
                    Those courses give you disconnected knowledge. We give you integrated experience.
                </p>
                <p>
                    They leave you alone when you get stuck. We guide you through the tough parts with a community and clear, project-based steps.
                </p>
                <p>
                    They end with a quiz. We end with you having a portfolio of apps that get you noticed.
                </p>
            </div>
        </section>

        <!-- OFFER STRUCTURE -->
        <section id="offer" class="py-20 sm:py-24 border-t border-slate-800 bg-slate-950/50 rounded-lg my-10">
            <div class="w-full max-w-3xl mx-auto text-center">
                <h2 class="fascination-headline">
                    What You Get Inside React Native Mastery
                </h2>
                <div class="text-left inline-block max-w-2xl mx-auto space-y-4 text-slate-300 mb-10">
                    <p class="flex items-center"><svg class="h-5 w-5 text-pink-500 mr-3" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg><strong class="text-white mr-2">Module 1:</strong> The Complete React Native & Expo Bootcamp</p>
                    <p class="flex items-center"><svg class="h-5 w-5 text-pink-500 mr-3" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg><strong class="text-white mr-2">Project 1:</strong> The Social Media App (Threads Clone)</p>
                    <p class="flex items-center"><svg class="h-5 w-5 text-pink-500 mr-3" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg><strong class="text-white mr-2">Project 2:</strong> The Streaming App (Netflix Clone)</p>
                    <p class="flex items-center"><svg class="h-5 w-5 text-pink-500 mr-3" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg><strong class="text-white mr-2">Project 3:</strong> The AI Agent App</p>
                    <p class="flex items-center"><svg class="h-5 w-5 text-pink-500 mr-3" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg><strong class="text-white mr-2">Projects 4-7:</strong> Advanced Real-World Applications</p>
                    <p class="flex items-center"><svg class="h-5 w-5 text-pink-500 mr-3" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg><strong class="text-white mr-2">PLUS:</strong> Community Access & Mentorship</p>
                </div>
                <div class="bg-slate-800 p-6 rounded-lg border border-slate-700 max-w-2xl mx-auto">
                    <p class="text-slate-300 mb-4">You can stop the cycle of unfinished projects today. It's time to build things you're proud to show off.</p>
                    <a href="#" class="cta-button inline-block w-full bg-pink-600 text-white font-bold text-lg px-10 py-4 rounded-lg shadow-lg hover:bg-pink-700">
                        Master React Native Now
                    </a>
                </div>
                 <div class="mt-8 text-center">
                    <p class="text-slate-400 font-bold">P.S. For those ready to go from idea to launch FAST...</p>
                    <p class="text-slate-500 mt-2">We run a pilot program called the notJust.Accelerator. The next cohort begins in January, and applications open in November. This is an intensive, guided program to help you launch a real startup or side project. Spots are extremely limited.</p>
                     <a href="#" class="mt-4 inline-block bg-slate-700 text-white font-bold text-md px-8 py-3 rounded-lg hover:bg-slate-600">
                        Join the Accelerator Waitlist
                    </a>
                </div>
            </div>
        </section>


        <!-- FAQ SECTION -->
        <section class="py-20 sm:py-24 border-t border-slate-800">
            <h2 class="fascination-headline">
                Your Questions, Answered.
            </h2>
            <div class="max-w-2xl mx-auto space-y-8">
                <div>
                    <h3 class="font-bold text-lg text-white mb-2">"What if I'm just a beginner?"</h3>
                    <p>This is built for developers who understand the basics of JavaScript and maybe some React. If that's you, you're in the right place. We start from the fundamentals of React Native & Expo and guide you every step of the way. The project-based approach means you learn by doing, which is the fastest way to solidify new skills.</p>
                </div>
                <div>
                    <h3 class="font-bold text-lg text-white mb-2">"Is this just another set of tutorials I won't finish?"</h3>
                    <p>This is the core problem we solve. Because every module results in a complete, portfolio-worthy app, the motivation is built-in. You're not just learning, you're creating a tangible asset. That feeling of finishing and having something to show for it is what will pull you through to the end.</p>
                </div>
                <div>
                    <h3 class="font-bold text-lg text-white mb-2">"I don't have time. How big is the commitment?"</h3>
                    <p>We know you're busy. The course is self-paced. But think about the time you're currently wasting on dead-end tutorials or debugging projects you abandon. This course focuses your time on what matters: building and shipping. Investing a few hours a week here will save you months, if not years, of frustration.</p>
                </div>
                 <div>
                    <h3 class="font-bold text-lg text-white mb-2">"What if I get stuck?"</h3>
                    <p>Unlike learning alone, you'll have access to a community of other builders and mentors. Getting stuck is part of the process—the difference is that here, you won't stay stuck for long. You'll get the help you need to push through roadblocks that would have otherwise killed your project.</p>
                </div>
                 <div class="text-center mt-16">
                     <p class="text-xl text-white font-bold mb-6">Stop collecting tutorials. Start building your legacy.</p>
                     <a href="#offer" class="cta-button inline-block bg-pink-600 text-white font-bold text-lg px-10 py-4 rounded-lg shadow-lg hover:bg-pink-700">
                        Build My First Real App
                    </a>
                </div>
            </div>
        </section>

        <footer class="text-center py-10 border-t border-slate-800">
            <p class="text-slate-500 text-sm">&copy; 2025. All Rights Reserved.</p>
        </footer>

    </div>

</body>
</html>
