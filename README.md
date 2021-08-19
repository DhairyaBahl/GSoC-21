<h1 align = "center"> Dhairya Bahl </h1>

<br>

<div  align="center">
	<a  href="https://summerofcode.withgoogle.com/projects/#4577622882779136"><img  src="https://user-images.githubusercontent.com/71627983/130011024-b36f3f0e-03db-4c7f-ab41-b077fe5327ef.png"  width="650"  alt="google-summer-of-code"></a>
	<br>
  <b>
		<p>
		    Google Summer Of Code 2021
		</p>
	</b>
</div>

This summer, I was pleased to get selected for Google Summer of Code'21 🚀 under the organization [Synfig Studio](https://github.com/synfig/).

## 📙 Abstract

Synfig is currently working on GTK 3.0 but some of the widgets of Synfig are still using the deprecated classes of GTK 2.0 . My task will be to find those classes and replace them with their appropriate alternative from GTK 3.0 which will make the code much more effective and will make it easier for us to later switch to upcoming GTK 4.0.

<div  align="center">

![enter image description here](https://media.giphy.com/media/ZcKASxMYMKA9SQnhIl/giphy.gif)

</div>

The purpose of creating this repository is to maintain a report summary of my GSoC work and this may also serve as a guide for future GSoC aspirants and a reference to the developers and contributors to the project.

<br>

## 🚀 Pre-GSoC period

In order to continue with this project, I had to learn using GNU Debugger (gdb). I spent most of my pre GSoC period learning using gdb. I followed [this](https://www.bitdegree.org/learn/gdb-debugger) link to learn about gdb.

I learnt the basics of gdb i.e. how breakpoints works, how to delete breakpoints and how to print and display variable values and some other basic stuff before moving onto the actual codebase.

Now after having some decent experience with debugging, I then decided to learn more about Synfig's codebase and was trying to become familiar with it.

## 💻 Coding Period Begins

During this period, I learnt a lot, made a lot of mistakes and then corrected them. This itself was a great experience for me.

Classes that I was able to migrate successfully were :

```
Gtk::HBox

Gtk::VScale

Implemented CSS classes, rather than using fixed width in main code 

Gtk::Alignment

Gtk::Application

Removed Gtk::Main

Gtk::HScale
```

Classes that were being migrated were ( work in progress ) : 

```
Gtk::UIManager

Gtk::StockID

Gtk::IconFactory
```

## 🚧 Challenges that I faced

During this period, I faced a lot of challenges. The very first challenge was to understand the overall Synfig's code. It took me few weeks to get the hang of code but eventually, I was able to understand what's happening under the hood. 

Later when I had to migrate to Gtk::Application from Gtk::Main, it was a challenge itself. I learnt about both of these from the docs ! Tried to make my own apps using Gtkmm, experimented on them and then later implemented the same code in Synfig.

**Reference Material that was of great use to me during these times:**

List of all deprecated Gtk classes : http://transit.iut2.upmf-grenoble.fr/doc/gtkmm-3.0/reference/html/deprecated.html

Official Gtk documentation : https://docs.gtk.org/gtk3/

Official Gtkmm documentation : https://developer-old.gnome.org/gtkmm-tutorial/3.18/

HowDoIs : https://wiki.gnome.org/HowDoI

Especially these were the most helpful ones : 

https://wiki.gnome.org/HowDoI/GtkApplication/ <br>
https://wiki.gnome.org/HowDoI/GAction <br>
https://wiki.gnome.org/HowDoI/ApplicationMenu <br>
https://wiki.gnome.org/HowDoI/GMenu <br>

## 🏁 Contributions

| PR Link| Description|
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------- |
| [#2187](https://github.com/synfig/synfig/pull/2187)  | Implementing Alignment and other classes |
| [#2195](https://github.com/synfig/synfig/pull/2195)  | Implemented CSS instead of deprecated width |
| [#2244](https://github.com/synfig/synfig/pull/2244)  | ``` Gtk::Main``` to ``` Gtk::Application``` Migration |
| [#2256](https://github.com/synfig/synfig/pull/2256)  | ``` Gtk::Action``` to ``` Gtk::SimpleAction``` Migration |
| [#2270](https://github.com/synfig/synfig/pull/2270)  | File Menu Migration using ``` Gtk::Builder``` |
| [#2256](https://github.com/synfig/synfig/pull/2256)  | ``` Gtk::ActionGroup``` to ``` Gtk::SimpleActionGroup``` Migration |

## ⚠️ Issues

| Issue Link | Description|
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------- |
| [#2123](https://github.com/synfig/synfig/issues/2123)  | Issue for Project Discussion with Mentors |

## 👨 Mentors

I would like to thank my mentors for helping me reach this milestone 😄🚀

During this period, I not only learnt about Open Source Culture but also about Industry level code.

* **Artem Konoplin** - [Github](https://github.com/ice0)
* **Rodolfo Ribeiro Gomes** - [Github](https://github.com/rodolforg)
* **Ankit Kumar Dwivedi** - [Github](https://github.com/ankit-kumar-dwivedi), [LinkedIn](https://www.linkedin.com/in/ankit-dwivedi)

## 🔗 Links

<div  align="center">

| **Student**      |                                                    Dhairya Bahl                                                     |
| :--------------- | :--------------------------------------------------------------------------------------------------------------------: |
| **Organization** |                           [Synfig-Studio](https://github.com/synfig/)                           |
| **Project**      | [Replacement Of Deprecated Gtk Classes](https://summerofcode.withgoogle.com/projects/#4577622882779136) |
| **GitHub**       |                                       [DhairyaBahl](https://github.com/DhairyaBahl/)                                        |
| **LinkedIn**     |                                [Dhairya Bahl](linkedin.com/in/dhairya-bahl/)                                |
| **Email**        |                    <a  href="mailto:dhairyabahl5@gmail.com">dhairyabahl5@gmail.com</a>                     |

</div>
