File-upload-library-for-CodeIgniter
===================================

File Upload Library.

<h3>Feature:</h3>
Image upload<br>
Video upload<br>
Image Resize<br>
Creating thumbnail<br>


<p>Configuration File Path.</p>
<code>application/config/file_upload.php</code>

<p>Image upload</p>
<code>do_image_upload($file_name, $folder_name = '')</code>
<p>Example:</p>
<code>$this->file_upload->do_image_upload('image');</code>

<p>Video upload</p>
<code>do_video_upload($file_name, $folder_name = '')</code>
<p>Example:</p>
<code>$this->file_upload->do_video_upload('video');</code>

<p>Image Resize</p>
<code>create_other_size($file_full_path)</code>
<p>Example</p>
<code>$this->file_upload->create_other_size($this->input->post('image_resize'))</code>


<p>Image Thumbnail</p>
<code>create_thumbnail($file_full_path)</code>
<p>Example</p>
<code>$this->file_upload->create_thumbnail($this->input->post('image_thumb'))</code>
