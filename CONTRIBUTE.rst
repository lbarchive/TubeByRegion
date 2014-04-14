==========
Contribute
==========

.. contents:: **Contents**
   :local:


Requirements
============

List of requirements to be pulled into this repository:

* **English** channel only

  I must review it, so it has to be in English.
  
  Although you can freely fork and add non-English channel as you like since this is hosted on GitHub and entirely project is in public domain, but please don't create pull request for that, it won't get merged to this repository.

* Strongly associated to a **region**

  Can be whole world, a continent, a country, a city, or as small as a town. Most likely it will be have the region in its title.

* **Regular** uploads

  It has to have regular uploads and is still active.

* Kind of **educational**

  By *educational*, I do not mean in academic sense. It's more like you don't watch a video, then feel you just waste 2 minutes and 30 seconds of your life for nothing. The channel certainly won't be some LOL, pranks, vlogs, etc.

  Topics like culture, history, tourism, cuisine, places, or people may be merged.
  
  Purely cookery or politics channel will not be accepted.

* *Commercial support* is a OK

  Many channels, even by governments, they are financially supported by corporations. Without those companies' donations, those channels probably wouldn't even be around in first place.

* Video length and quality don't matter

  1 minute, 5 minutes, or 1 hour doesn't matter. The quality of videos doesn't matter much, either. However, it has to be more than watchable.

* Producer doesn't matter

  Who produces the channel doesn't matter. No matter is by government, NGO, or individual, as long as the content quality is good, I will merge.


Content quality
===============

I will give three sample channels to show you the quality of channels that meets my standards, and you can understand the styles of channels I am interested in.

* `INDIE ALASKA`_

  This is the best quality I would recommend. I don't think I have seen any commercial plug-in in any of its videos.

  It introduce the culture, the people, and the business of Alaska. It's produced by Alaska Public Media.

* `America's Heartland`_

  This has very minimal commercial support mentions, only in the end of episodes I believe.

  It covers entire United States, about agriculture mainly. It's funded by Farm Credit and Crop Life America. Americas Heartland is produced by KVIE, public television, in Sacramento, California.

* `Discover Oklahoma`_

  This has reached my limitation on the commercial support, it even has a company name in the logo, and has many commercials in the video.

  Nonetheless, it's produced by the Oklahoma Tourism and Recreation Department.

.. _Indie Alaska: https://www.youtube.com/user/alaskapublicmedia
.. _America's Heartland: https://www.youtube.com/user/americasheartland
.. _Discover Oklahoma: https://www.youtube.com/user/DiscoverOklahoma


How to contribute
=================

* Better to ask_ first if you want to be pulled

  If you want to be pulled, ask first just to be sure, or you might get rejected because I don't like the channels you add.

* Create a reStructuredText (``.rst``) for the region

  Using reST because we need Table of Contents, Markdown on GitHub doesn't have such extension. And frankly, reST is a better format.

  * If a folder is needed and not yet created, then create one as well.
  * If a split is need, then do it.

* Add to the list

  Use channel *styled* title if possible, and link to the channel. They may look like:

  .. code:: rst

    # Region 1

    * `foobar1`_

    .. _foobar1: http://youtube.com/user/{user}


    # Region 2

    * `foobar2`_: *the tagline*

    .. _foobar2: http://youtube.com/channel/{channel}

* Description is not required, tagline is optional

  Maybe no description is better, to keep the list clean.

  If there is a tagline around--like in logo, and it is clear and short enough, then put it on in the same way in the example above. Separate title and tagline with ":" and make tagline italics. Keep letter cases as in the original tagline, keep the styled text if possible.

* Commit and push

  Clear commit message about the added channel. "add a channel" isn't acceptable. Good commit message example::

    add foobar1 and foobar2

* Create a pull request

  Upon creating the request, you agree to put your contribution in *public domain*.

.. _ask: https://github.com/livibetter/TubeByRegion/issues/1
