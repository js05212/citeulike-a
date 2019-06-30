This dataset, citeulike-a, was used in the paper 'Collaborative Topic Regression with Social Regularization' [Wang, Chen and Li]. It was collected from CiteULike and Google Scholar. CiteULike allows users to create their own collections of articles. There are abstracts, titles, and tags for each article. Other information like authors, groups, posting time, and keywords is not used in this paper 'Collaborative Topic Regression with Social Regularization' [Wang, Chen and Li]. The details can be found at http://www.citeulike.ort/faq/data.adp. 

It is partly from [Wang and Blei]. Note that the original dataset in [Wang and Blei] does not contain relations between items. We collect the tag information from CiteULike and citations from Google Scholar.

The text information (item content) of citeulike-a is preprocessed by following the same procedure as that in [Wang and Blei].

Some statistics are listed as follows£º

#users 					5551 
#items 					16980 
#tags 					46391 
#citations 				44709
#user-item pairs 		204987 

DATA FILES
citations.dat	citations between articles
item-tag.dat	tags corresponding to articles, one line corresponds to tags of one article (note that this is the version prior to preprocess thus would have more tags than used in the paper)
mult.dat		bag of words for each article
raw-data.csv	raw data
tags.dat		tags, sorted by tag-id's
users.dat		rating matrix (user-item matrix)
vocabulary.dat	corresponding words for file mult.dat

BibTex
@inproceedings{DBLP:conf/ijcai/WangCL13,
  author    = {Hao Wang and
               Binyi Chen and
               Wu-Jun Li},
  title     = {Collaborative Topic Regression with Social Regularization
               for Tag Recommendation},
  booktitle = {IJCAI},
  year      = {2013},
  ee        = {http://www.aaai.org/ocs/index.php/IJCAI/IJCAI13/paper/view/7006},
  crossref  = {DBLP:conf/ijcai/2013},
  bibsource = {DBLP, http://dblp.uni-trier.de}
}

@proceedings{DBLP:conf/ijcai/2013,
  editor    = {Francesca Rossi},
  title     = {IJCAI 2013, Proceedings of the 23rd International Joint
               Conference on Artificial Intelligence, Beijing, China, August
               3-9, 2013},
  booktitle = {IJCAI},
  publisher = {IJCAI/AAAI},
  year      = {2013},
  isbn      = {978-1-57735-633-2},
  bibsource = {DBLP, http://dblp.uni-trier.de}
}