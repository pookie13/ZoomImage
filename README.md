# ZoomImage
A simple Repo that help to make your image zoomable on touch or pin to zoom.
for this purpose you just copy and past this class into your code.
and put below lines into your xml files like:
``` <your_packege_name.TouchImageView
        android:id="@+id/frag_imageview"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:scaleType="fitCenter"
        android:src="@drawable/default_flag"
        android:transitionName="@string/transition_name_phone" /> 
       
       

  <ImageView
        android:id="@+id/frag_imageview"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:scaleType="fitCenter"
        android:src="@drawable/default_flag"
        android:transitionName="@string/transition_name_phone" />
  ```
  and now into your Activity find this view like:
  
  ```TouchImageView tv=(TouchImageView)findViewById(R.id.frag_imageview);
     tv.setImageResource(R.drawable.ic_play);```
     
     so thats it. now your simple image will able to pin to zoom and double tap image view to zoom.
