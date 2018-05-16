# Collections
*  _student_
    * _id : mongo id
    * name : english name
    * hebName : hebrew name
    * birthdate:  int :  timestamps
    * image : url to image
    * entryChallangeGrade : the grade in the entry challange
* _staffMember_
    * _id : mongo id
    * name: engilsh name
    * hebName: hebew name
* _review_
    * _id : mongo id
    * grade : 1 - 10
    * description : text 
    * staffMember : id from the _staffMember_ collections.
    * student : id from the _student_ collections
    * date : ISODate - (not created at)