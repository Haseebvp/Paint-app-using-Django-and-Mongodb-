from django.conf.urls import patterns, include, url

# Uncomment the next two lines to enable the admin:
# from django.contrib import admin
# admin.autodiscover()

urlpatterns = patterns('',
    # Examples:
	url(r'^$',welcome),
	url(r'^home/$',home),
	url(r'^save/$',save),
	url(r'^gallery/$',gallery),
	url(r'^home/gallery/$',gallery),
	url(r'^gallery/close/$',welcome),
	url(r'^gallery/([^/]+)/$',load),
    # url(r'^$', 'mongodbproject.views.home', name='home'),
    # url(r'^mongodbproject/', include('mongodbproject.foo.urls')),

    # Uncomment the admin/doc line below to enable admin documentation:
    # url(r'^admin/doc/', include('django.contrib.admindocs.urls')),

    # Uncomment the next line to enable the admin:
    # url(r'^admin/', include(admin.site.urls)),
)
