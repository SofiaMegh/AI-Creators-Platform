# 🧠 AI Creators Platform CMS

> ⚠️ **Demo Project – Experimental Build**
> ▲ This project is a proof-of-concept and experimental implementation of a full-stack AI-powered CMS for creators.
> It serves as a demo before the final version is customised and deployed for a client.

## 🚀 Platform Overview

The **AI Creators Platform CMS** blends cutting-edge AI tools with intuitive UI/UX design to empower creators. Users can craft content using AI-assisted text generation, manage images and videos with advanced transformations, and engage with a collaborative creator network.

## ✨ Key Features

* **AI-Powered Content Generation**

  * Seamless AI text generation and manual editing via React Quill.
  * Options to expand, simplify, or refine content in real time.

* **Image & Video Management**

  * Integrated with [ImageKit](https://imagekit.io/) for uploads, transformations, and optimization.
  * Includes background removal, cropping, shadows, overlays, and aspect-ratio control.

* **Authentication & User Management**

  * Secure auth powered by [Clerk](https://clerk.dev/), supporting social logins and user profiles.

* **Real-Time Backend & Database**

  * Built on [Convex](https://www.convex.dev/) for reactive data sync across users.

* **UI/UX Excellence**

  * Modern stack using [Next.js 15](https://nextjs.org/), [React 19](https://react.dev/), [Tailwind CSS](https://tailwindcss.com/), and [Shadcn UI](https://ui.shadcn.com/).

* **Social Features**

  * Profiles, likes, comments, and “For You”/“Trending” feeds.

* **Analytics Dashboard**

  * Post performance, follower metrics, engagement heatmaps, and daily trends.

## 🔄 User Flows

1. **Sign Up / Login** – via Clerk
2. **Create & Edit** – rich text + AI assistant
3. **Publish & Discover** – share and browse in the feed
4. **Track Performance** – via analytics dashboard

## 🧰 Tech Stack

| Layer         | Tools & Libraries                                |
| :------------ | :----------------------------------------------- |
| **Frontend**  | React 19, Next.js 15, Tailwind CSS, Shadcn UI    |
| **Backend**   | Convex (real-time DB), third-party APIs          |
| **Auth**      | Clerk                                            |
| **AI/ML**     | Generative models for text and image processing  |
| **Dev Tools** | CodeRabbit (for reviews), Vercel for deployments |

## 📈 Why I built this?

This experimental build demonstrates:

* Deep AI integration across text, media, and analytics.
* Real-time collaboration features.
* Modular, scalable architecture for production systems.
