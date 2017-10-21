                  Prefix Verb   URI Pattern                       Controller#Action
             rails_admin        /admin                            RailsAdmin::Engine
        new_user_session GET    /users/sign_in(.:format)          devise/sessions#new
            user_session POST   /users/sign_in(.:format)          devise/sessions#create
    destroy_user_session DELETE /users/sign_out(.:format)         devise/sessions#destroy
           user_password POST   /users/password(.:format)         devise/passwords#create
       new_user_password GET    /users/password/new(.:format)     devise/passwords#new
      edit_user_password GET    /users/password/edit(.:format)    devise/passwords#edit
                         PATCH  /users/password(.:format)         devise/passwords#update
                         PUT    /users/password(.:format)         devise/passwords#update
cancel_user_registration GET    /users/cancel(.:format)           devise/registrations#cancel
       user_registration POST   /users(.:format)                  devise/registrations#create
   new_user_registration GET    /users/sign_up(.:format)          devise/registrations#new
  edit_user_registration GET    /users/edit(.:format)             devise/registrations#edit
                         PATCH  /users(.:format)                  devise/registrations#update
                         PUT    /users(.:format)                  devise/registrations#update
                         DELETE /users(.:format)                  devise/registrations#destroy
       user_confirmation POST   /users/confirmation(.:format)     devise/confirmations#create
   new_user_confirmation GET    /users/confirmation/new(.:format) devise/confirmations#new
                         GET    /users/confirmation(.:format)     devise/confirmations#show
           confirm_blogs POST   /blogs/confirm(.:format)          blogs#confirm
                   blogs GET    /blogs(.:format)                  blogs#index
                         POST   /blogs(.:format)                  blogs#create
                new_blog GET    /blogs/new(.:format)              blogs#new
               edit_blog GET    /blogs/:id/edit(.:format)         blogs#edit
                    blog PATCH  /blogs/:id(.:format)              blogs#update
                         PUT    /blogs/:id(.:format)              blogs#update
                         DELETE /blogs/:id(.:format)              blogs#destroy
        confirm_contacts POST   /contacts/confirm(.:format)       contacts#confirm
                contacts POST   /contacts(.:format)               contacts#create
             new_contact GET    /contacts/new(.:format)           contacts#new
                   poems GET    /poems(.:format)                  poems#index
                    poem GET    /poems/:id(.:format)              poems#show
                    root GET    /                                 top#index
       letter_opener_web        /letter_opener                    LetterOpenerWeb::Engine

Routes for RailsAdmin::Engine:
  dashboard GET         /                                      rails_admin/main#dashboard
      index GET|POST    /:model_name(.:format)                 rails_admin/main#index
        new GET|POST    /:model_name/new(.:format)             rails_admin/main#new
     export GET|POST    /:model_name/export(.:format)          rails_admin/main#export
bulk_delete POST|DELETE /:model_name/bulk_delete(.:format)     rails_admin/main#bulk_delete
bulk_action POST        /:model_name/bulk_action(.:format)     rails_admin/main#bulk_action
       show GET         /:model_name/:id(.:format)             rails_admin/main#show
       edit GET|PUT     /:model_name/:id/edit(.:format)        rails_admin/main#edit
     delete GET|DELETE  /:model_name/:id/delete(.:format)      rails_admin/main#delete
show_in_app GET         /:model_name/:id/show_in_app(.:format) rails_admin/main#show_in_app

Routes for LetterOpenerWeb::Engine:
clear_letters DELETE /clear(.:format)                 letter_opener_web/letters#clear
delete_letter DELETE /:id(.:format)                   letter_opener_web/letters#destroy
      letters GET    /                                letter_opener_web/letters#index
       letter GET    /:id(/:style)(.:format)          letter_opener_web/letters#show
              GET    /:id/attachments/:file(.:format) letter_opener_web/letters#attachment
